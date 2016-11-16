#Shape
##Linux
```
sudo nano /etc/apt/sources.list
deb http://ftp.belnet.be/debian/stretch main contrib non-free
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get autoremove
sudo reboot (new kernel)
```
##System
```
sudo apt-get install ansible git openssh-server
ssh-keygen
ssh-copy-id -i .ssh/id_rsa.pub debian-vm
git clone https://github.com/Jooltje/shape.git
cd shape
ansible-playbook -K -i production site.yml
```
##VirtualBox (optional)
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential module-assistant
sudo m-a prepare
sudo mount /media/cdrom
sudo sh /media/cdrom/VBoxLinuxAdditions.run
sudo reboot
```
##Desktop
```
startx
```
