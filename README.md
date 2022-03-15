## Switch to root user, then run the following one-line command

Centos:
yum install git -y && cd && git clone https://github.com/yzw2333/ov && cd ov && ./openvpn-install.sh 1

Ubuntu/Debian:
apt install git -y && cd && git clone https://github.com/abbrous/ov && cd ov && ./openvpn-install.sh hk_xiaoming

然后取回hk_xiaoming.ovpn文件，或者cat hk_xiaoming.ovpn 然后复制粘贴建立新文件，就不用从服务器上下载了。

新增新用户，给张三产生客户端文件示例，用户名前面可以加上服务器地理位置，方便标记 例如香港 hk_ 美国usa_ 日本东京 tokyo_
./openvpn-install usa_zhangsan


## Download xxx.ovpn file, and import to you client
MACOS client => Tunnelblick<br>
Android Phone client => Openvpn for Android<br>
iOS Phone client => Openvpn from Apple App Store<br>
Windows PC => Openvpn Client for Windows<br>
Linux Distro: install openvpn package, run as root : openvpn --config xxx.ovpn<br>

Forked from Nyr/openvpn-install . 
