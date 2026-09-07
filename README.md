# DeleteVentoySecureBootKey
How to delete the secure boot key enrolled by Ventoy?  ===>  [https://www.ventoy.net/en/doc_delete_key.html](https://www.ventoy.net/en/doc_delete_key.html)


如何删除Ventoy导入的安全启动Key? ===> [https://www.ventoy.net/cn/doc_delete_key.html](https://www.ventoy.net/cn/doc_delete_key.html)

# About Source Code 

All the files in the ISO file are either directly from upsteam project (e.g. EFI files/vmlinux/.so/mokutil ...)  (RockyLinux 9) or plain shell script.
The core functions are in the `ventoy_delete_key.sh` script which can get it after decompress the `EFI/BOOT/initrd.cpio.gz` file.


