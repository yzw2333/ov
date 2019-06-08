# One Click to Configure OpenVPN Server

## OS requirements: Ubuntu Centos Debian

## install git
apt install git -y . 
yum install git -y . 

## clone this bash script
git clone https://github.com/abbrous/openvpn-install

## change directory, switch to root account, add executable permission
cd openvpn-install . 
chmod a+x openvpn-install.sh . 
./openvpn-install.sh . 

## close firewall, or permit port 9090(anything you want), e.g systemctl stop firewalld
## server xxx.ovpn file, open your browser and download
python -m SimpleHTTPServer 9090 . 

## download xxx.ovpn file, and import to you client

MAC OS X client => Tunnelblick . 
Android Phone client => Openvpn for Android . 
iOS Phone client => Openvpn for Android . 
Windows PC => Openvpn for Android . 
Linux Distro: install openvpn package, run as root : openvpn --config xxx.ovpn . 

Forked from Nyr/openvpn-install . 
