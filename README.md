# elitebook-840-g5

CLover configuration for a perfect vanilla CLOVER installation on HP Elitebook 840 G5 

Credits go to kinoute by whome i was insired, files are also available at Github

https://github.com/kinoute/Hack-HP-EliteBook-850-G5

Download ZIP and copy files under your EFI disk partition in /EFI/CLOVER/

Currently verified and working in Catalina 10.15.3 :

- Trackpad I2C VoodooI2C and VoodooI2CHID (Trackpad preferences enabled and working as expected)
- WiFI replaced the Intel Wifi with Dell 1820a
- Integrated LAN
- Battery indications, battery status OK
- Audio input/output and mic working
- Camera working
- Integrated iGPU working Intel 620
- USB all working
- Docking station working and docking station HDMI is working as dual monitor
- Clover 5112 
- Sleep, Wake, WiFi working after wake
- Brightness control
- Volume control through keyboard
- NVME, Replaced non-working Samsung PM981 with Crusial P1


Not Working / Not Tested :

- Bluetooth (Installed a USB bluetooth dongle)
- Fingerprint sensor (Not really tested)
- SD Card reader, tried Sinetek kext but couldnt make it to work
- HDMI Audio, not tested



