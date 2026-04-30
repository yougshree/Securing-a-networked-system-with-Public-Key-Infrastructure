## How to copy from a computer to Ubuntu:
# Step 1:
- Clipboard → Bidirectional
- Drag & Drop → Bidirectional
# Step 2:
- In running Ubuntu VM, go to the VirtualBox menu bar at the top: Devices → Insert Guest Additions CD Image
# Step 3:  Install it in the Ubuntu terminal
- sudo apt update
- sudo apt install build-essential dkms linux-headers-$(uname -r)
- sudo mount /dev/cdrom /mnt
- cd /mnt
- sudo ./VBoxLinuxAdditions.run
# Step 4: Reboot the VM
- sudo reboot
