# Ilak
Setup Scripts and such for more efficent use of resources.

#Be sure to update / upgrade as needed

$sudo apt-get update 
$sudo apt-get upgrade

#Get a VPN Service up I prefer GoldenFrog for their speed and location
#After you have an acct grab the deb cli pkg
$ wget https://support.goldenfrog.
com/hc/article_attachments/360010562332/vyprvpn-linux-cli-1.7.amd64.deb
$ sudo apt install ~/vyprvpn-linux-cli-1.7.amd64.deb

# restart network manager
systemctl restart NetworkManager.service




#Install Tor to bounce around or use tcp joke if your neighbor is capturing your packets

#Install Snort IDS and keep a log 
