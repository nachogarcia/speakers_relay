# speakers_relay
Switch the power of your speakers in RuneAudio with a relay using Telnet, Expect and WiringPi

Installation
```
pacman -S wiringpi
pacman -S expect
```
Copy the files to your desired location (e.g: /etc/scripts/speakers_relay.exp and /etc/systemd/system/speakers_relay.service) and enable it.
`systemctl enable speakers_relay.service`
