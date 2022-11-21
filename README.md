<h1 align="center">WIPWN</h1>
<h4 align="center">Hack WIfi Using Termux! (Requires Root)</h4>

#### Start

<p align="center"><img src="https://raw.githubusercontent.com/ITSN0B1T4/itsn0b1t4.github.io/main/wepwn/.assets/demo2.png"></p>

#### Cracked

<p align="center"><img src="https://raw.githubusercontent.com/ITSN0B1T4/itsn0b1t4.github.io/main/wepwn/.assets/demo3.png"></p>

#### Autostart if failed 

<p align="center"><img src="https://raw.githubusercontent.com/ITSN0B1T4/itsn0b1t4.github.io/main/wepwn/.assets/demo4.png"></p>

### Installation :

```bash
pkg update && pkg upgrade -y
pkg install root-repo -y
pkg install git tsu python termux-api wpa-supplicant pixiewps iw -y
git clone https://github.com/ITSN0B1T4/wipwn
cd wipwn
chmod +x wipwn.py
```
#### Help : `sudo python wipwn.py --help`
#### Example : `sudo python wipwn.py -i wlan0 -K`

#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python wipwn.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python wipwn.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python wipwn.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**

### License

````
MIT License

Copyright (c) 2022 Toxinum.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
````

+ **IF FAILED TURN OFF LOCATION IF TURNED ON.**

Repo : <a href="https://github.com/ITSN0B1T4/wepwn"> Here </a>

##### Modify History : rofl0r => Biri_B@B@ => Mohammad_Alamin (Toxinum)
<div align="center">
<h3>━━━━ Connect with me ━━━━</h3>
<a href="https://fb.com/TOXINUM" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="TOXIC-VIRUS" height="30" width="40" /></a>
<a href="https://twitter.com/itzakx21" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="itzakx21" height="30" width="40" /></a>
<a href="https://fb.com/ITSN0B1T4" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Mohammad Alamin" height="30" width="40" /></a>
<a href="https://instagram.com/ITSN0B1T4" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="akxvau" height="30" width="40" /></a>
</div>
