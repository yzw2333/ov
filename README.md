# One Click to Configure OpenVPN Server

## OS requirements: Ubuntu Centos Debian

## install git
apt install git -y<br>

yum install git -y<br>


## clone this bash script
git clone https://github.com/abbrous/openvpn-install

## change directory, switch to root account, add executable permission
cd openvpn-install<br>
chmod a+x openvpn-install.sh<br>
./openvpn-install.sh<br>

## close firewall, or permit port 9090(anything you want), e.g systemctl stop firewalld
## server xxx.ovpn file, open your browser and download
python -m SimpleHTTPServer 9090<br>

## download xxx.ovpn file, and import to you client

MAC OS X client => Tunnelblick<br>
Android Phone client => Openvpn for Android<br>
iOS Phone client => Openvpn for Android<br>
Windows PC => Openvpn for Android<br>
Linux Distro: install openvpn package, run as root : openvpn --config xxx.ovpn<br>

Forked from Nyr/openvpn-install . 
