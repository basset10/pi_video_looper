# pi_video_looper
A fork of Adafruit's pi_video_looper for personal use.
https://github.com/adafruit/pi_video_looper

Currently only the __Legacy__ version of Raspberry Pi OS Lite is supported.  
Download here:
<https://downloads.raspberrypi.com/raspios_oldstable_lite_armhf/images/raspios_oldstable_lite_armhf-2022-01-28/2022-01-28-raspios-buster-armhf-lite.zip>

This program has been tested on the Raspberry Pi Zero 2 W

## Setup
For maximum compatibility ensure the username on your Raspberry Pi is "pi".  
`sudo apt-get update`  
`sudo apt-get install git `  
`sudo git clone https://www.github.com/basset10/pi_video_looper.git`  
`cd pi_video_looper/assets`  
`sudo cp ring.ttf /home/pi/`  
`sudo cp loader.png /home/pi/`  
Repeat the above command as many times as needed. Currently up to 12 loader images are supported (loader.png, loader2.png, etc).  
`cd ..`  
`sudo ./install.sh`  

## Updating
Plug in a keyboard and press ESC to access the terminal.    
`cd ~`   
`sudo rm -rf pi_video_looper`   
`sudo git clone https://github.com/basset10/pi_video_looper.git`    
`cd pi_video_looper`   
`sudo ./install.sh` 
