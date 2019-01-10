# Ilak
Setup Scripts and such for more efficent use of resources.

# Be sure to update / upgrade as needed

$sudo apt-get update 
$sudo apt-get upgrade

# Get a VPN Service install & up I prefer GoldenFrog for their speed and location
#After you have an acct grab the deb cli pkg
$ wget https://support.goldenfrog.
com/hc/article_attachments/360010562332/vyprvpn-linux-cli-1.7.amd64.deb
$ sudo apt install ~/vyprvpn-linux-cli-1.7.amd64.deb

#Change Managed to True Save 

$ nano /etc/NetworkManager/NetworkManager.conf

#restart network manager and/or linux
$ systemctl restart NetworkManager.service

#Login to vyprn
$vyprvpn login 
#provide creditials

#next setupserver (locations here: https://support.goldenfrog.com/hc/en-us/articles/360011055671-What-are-the-VyprVPN-server-addresses-)
$ vyprvpn server set us2.vpn.goldenfrog.com 
#Next use the vyprnvpn protocol set command and choose 4 e.g 
$vyprvpn protocol set
Your screen output ...
$ VyprVPN Protocols
 1: pptp
 2: openvpn160
 3: openvpn256
 4: chameleon
Please enter the number of your selection:
4
Success: chameleon set as new default
#next turn it on / off using connect and disconnect
$ vyprvpn connect
Succes! VyprnVPN Connected.


================================================================================================

Install Snort 

================================================================================================

$ apt-get install snort






$vyprvpn server set us2.vpn.goldenfrog.com




#Install Tor to bounce around or use tcp joke if your neighbor is capturing your packets

#Install Snort IDS and keep a log 
