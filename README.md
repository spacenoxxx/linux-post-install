# Debian-titus
Debian customizations from Chris Titus Tech
 
## Requirements
_This install changes Debian to the SID (Dev) Branch_

### Download Debian non-free netinstall

Use the following Debian ISO as the base <https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/weekly-builds/amd64/iso-cd/>

*do NOT grab the EDU download and this includes non-free and firmware*
### To install:

```
sudo apt install git -y
mkdir -p github
cd github
git clone https://github.com/spacenoxxx/linux-post-install
cd linux-post-install
sudo ./install.sh
```

