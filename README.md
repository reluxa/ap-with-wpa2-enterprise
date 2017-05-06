# ap-with-wpa2-enterprise
Tutorial for Raspberry Pi 3 to function as an AP with WPA2-Enterprise authentication

## Sources:
https://www.raspberrypi.org/documentation/configuration/wireless/access-point.md
https://wiki.archlinux.org/index.php/Internet_sharing

## Interfaces:
* wlan1 -> wifi bundle to function as AP
* eth0 -> interface with internet access

## Steps:
* [create AP with WPA2-PSK](../master/ap_wpa_psk)
  * install packages
  * configure AP network interface
  * configure DHCP
  * configure AP hosting
  * configure NAT
  * test AP
* [upgrade authentication to WPA2-Enterprise]()

