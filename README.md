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
