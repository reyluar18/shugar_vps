# Premium AutoScript

Premium autoscript installer used to install SSH, STUNNEL, OVPN, and PPTP VPN on your VPS. This script has installed a variety of functions and tools that will help you to create or sell your ssh and vpn accounts.

### Installation:

##VPS

- Centos 6 x86 & x64

`yum -y update && yum -y install wget && wget https://raw.githubusercontent.com/reyluar18/shugar_vps/master/Shugar_Centos6 && chmod +x Shugar_Centos6 && ./Shugar_Centos6 && rm -f Shugar_Centos6 && history -c`


- Debian 8 x86 & x64

`apt-get -y install wget && wget https://raw.githubusercontent.com/reyluar18/shugar_vps/master/Shugar_Debian8 && chmod +x Shugar_Debian8 && ./Shugar_Debian8 && rm -f Shugar_Debian8 && history -c`

## OCS

- Debian
`apt-get -y install wget && wget https://raw.githubusercontent.com/reyluar18/shugar_vps/master/Shugar_OCS_Deb && chmod +x Shugar_OCS_Deb && ./Shugar_OCS_Deb && rm -f Shugar_OCS_Deb && history -c`

- Centos
`yum -y update && yum -y install wget && wget https://raw.githubusercontent.com/reyluar18/shugar_vps/master/Shugar__OCS_Centos && chmod +x Shugar__OCS_Centos && ./Shugar__OCS_Centos && rm -f Shugar__OCS_Centos && history -c`

###ANTI-BLOCK

`wget https://raw.githubusercontent.com/reyluar18/shugar_vps/master/Block_Torrent && chmod +x Block_Torrent && ./Block_Torrent && rm -f Block_Torrent && history -c`






### Important Information:

- Fail2Ban

- Ddos Deflate

- IP Tables

- Webmin - http://VPSIP:10000/

- VnStat - http://VPSIP:85/vpnstat/

- MRTG - http://VPSIP:85/mrtg/

- OVPN Config - http://VPSIP:85/client.ovpn | http://VPSIP:85/openvpn.tar.gz or http://VPSIP:85/client.tar for Centos


### Service and Port Informations:

- OpenVPN : TCP 1194

- OpenSSH : 22 & 143

- Stunnel/4 : 443

- Dropbear : 109, 110 & 442

- Squid Proxy : 80, 8000, 8080, 8888 & 3128

- PPTP VPN : 1732

- Badvpn : 7300

- Nginx : 85


### Server Tools:

- htop

- iftop

- mtr

- nethogs

- screenfetch


### Credits:

Hosting Termurah & VPS-Murah

