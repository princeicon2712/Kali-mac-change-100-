# mac-change/ip change




## Automatic mac change 25-30 Secaucus


python3 Automatic-MAC-Address-Changer.py -i wlan0 -t 25




## ip chang

apt install grep -y

nano ip.sh

read ip

ifconfig wlan0 down

ifconfig wlan0 $ip

ifconfig wlan0 I grep $ip

ifconfig wlan0 up

ifconfig




## Network adapter:

ifconfig wlan0 down

## Change the address using hw ether option from ifconfig using any MAC address you want:

ifconfig wlan0 hw ether 00:11:22:33:44:55

## Enable the interface:

ifconfig wlan0 up

## Check the changes of the network adapter:

ifconfig


# automatic Mac change:--

nano rendom.sh




read mac

ifconfig wlan0 down

ifconfig wlan0 hw ether $mac

ifconfig wlan0 up


ifconfig wlan0 down

ifconfig wlan0 hw ether $mac

ifconfig wlan0 up

ifconfig



## mac change link:-

nano macc.sh

ifconfig wlan0 down
macchanger -r wlan0
ifconfig wlan0 up
ifconfig 


