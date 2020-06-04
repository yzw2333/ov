
## OS: Ubuntu Centos Debian

## Install git
apt install git -y<br>

yum install git -y<br>


## Clone this bash script
git clone https://github.com/abbrous/ov

## Change into directory, switch to root account, add executable permission
cd ov<br>
chmod +x openvpn-install.sh
### switch to root user
sudo su
openvpn-install.sh client_username

## Stop firewall, or permit port 9090(anything you want), e.g systemctl stop firewalld
## Serve xxx.ovpn file, open your browser and download
python -m SimpleHTTPServer 9090<br>


## Download xxx.ovpn file, and import to you client

MACOS client => Tunnelblick<br>
Android Phone client => Openvpn for Android<br>
iOS Phone client => Openvpn from Apple App Store<br>
Windows PC => Openvpn for Windows<br>
Linux Distro: install openvpn package, run as root : openvpn --config xxx.ovpn<br>

Forked from Nyr/openvpn-install . 
