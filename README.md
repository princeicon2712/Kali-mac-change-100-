# Kali-mac-change-100-


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



