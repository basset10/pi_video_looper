# pi_video_looper
A fork of Adafruit's pi_video_looper for personal use.
https://github.com/adafruit/pi_video_looper

Currently only the __Legacy__ version of Raspberry Pi OS Lite is supported.  
Download here:
<https://downloads.raspberrypi.com/raspios_oldstable_lite_armhf/images/raspios_oldstable_lite_armhf-2022-01-28/2022-01-28-raspios-buster-armhf-lite.zip>

## Setup
For maximum compatibility ensure the usename on your Raspberry Pi is "pi".
`sudo apt-get update`  
`sudo apt-get install git `  
`git clone https://www.github.com/basset10/pi_video_looper.git`  
`cd pi_video_looper`  
`sudo ./install.sh`  

## Updating
Plug in a keyboard and press ESC to access the terminal.    
`cd ~`   
`sudo rm -rf pi_video_looper`   
`git clone https://github.com/basset10/pi_video_looper.git`    
`cd pi_video_looper`   
`sudo ./install.sh` 
