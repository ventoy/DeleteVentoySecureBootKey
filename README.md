# DeleteVentoySecureBootKey
How to delete the secure boot key enrolled by Ventoy.

1. Download `delete_key_injection.tar.gz` from release [https://github.com/ventoy/DeleteVentoySecureBootKey/releases](https://github.com/ventoy/DeleteVentoySecureBootKey/releases)

2. Set `delete_key_injection.tar.gz` as the injection achieve for Fedora Workstation ISO file (e.g. `Fedora-Workstation-Live-x86_64-36-1.5.iso`) by [Ventoy Injection Plugin](https://www.ventoy.net/en/plugin_injection.html) 

3. Boot Fedora Workstation ISO by Ventoy

4. After boot into Fedora Workstation run `sudo sh /home/ventoy_delete_key.sh` in the terminal. (It will reboot the system after executed.)

5. After reboot you will run into blue MokManager screen.  
   Select `Delete MOK` ---> `Continue` ---> `Yes` then enter password `123` to confirm and finally select `Reboot`. 

Here the secure boot key enrolled by Ventoy is completely removed from your computer.

