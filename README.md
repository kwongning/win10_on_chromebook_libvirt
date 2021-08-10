# Win10 VM on chromebook by libvirt
Install Win 10 on Samsung Galaxy Chromebook with libvirt

Step 1: Enable Linux in Chrome OS  
Step 2: Open Terminal  
Step 3: Run "sudo apt-get update"  
Step 4: Run "sudo apt-get upgrade" * the distro will become Debian 10.10+  
Step 5: Run "sudo apt install qemu-kvm libvirt-clients libvirt-daemon-system bridge-utils virtinst libvirt-daemon virt-manager -y"  
Step 6: Create VM with Win 10 iso and virtIO driver iso  

Install RDP Client  
sudo apt install remmina remmina-plugin-vnc  
