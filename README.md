# wpa
simple sh script to work with wpa_supplicant if you're lazy enough to use long commands

# Dependencies
* wpa_supplicant
* iw
* dhcpcd

# How to use
```
put the script in $PATH and run it as root.
```
## EXAMPLE
```
1)
# wpa -s
output:
WIFI_OF_YOUR_NEIGHBOUR
HOME_SWEET_HOME
RICHARD_STALLMANS_WIFI
LINUS_TORVALDS_WIFI

2)
# wpa -a HOME_SWEET_HOME PASSWORD

3)
# wpa -c HOME_SWEET_HOME
```

# HELP PAGE
```
scan[--scan|-s]: scans for available wireless networks around you.

add[--add|-a]: adds a network.

connect[--connect|-c]: connects to a network.

cl[-cl] connects to the last connected network.

disconnect[--disconnect|-d]: disconnects from the web.

forget[--forget|-f]: removes a network from saved.

help[--help|-h]: opens this page.
```
