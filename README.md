# broadcom_BCM43142_4.14.0-kali3-amd64_driver
how to make the wifi (BCM43142) works in kali 4.14.0 
you can download the driver from the repository or from here

https://packages.debian.org/sid/all/broadcom-sta-dkms/download

# then execute this commands: 

apt update && apt dist-upgrade
apt install gdebi linux-headers-4.14.0-kali3-amd64

# after downloading just download broadcom-sta-dkms_6.30.223.271-7_all.deb google it then cd to the downloded file then execute

gdebi downloaded_file.deb
modprobe wl

# useful commands: 

wifi card\n
lspci | grep BCM

kernel version
uname -r



