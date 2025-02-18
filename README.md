# pi_video_looper
A fork of Adafruit's Pi Video Looper for personal use.
https://github.com/adafruit/pi_video_looper

Currently only the __Legacy__ version of Raspberry Pi OS Lite is supported.  
Download here:
<https://downloads.raspberrypi.com/raspios_oldstable_lite_armhf/images/raspios_oldstable_lite_armhf-2022-01-28/2022-01-28-raspios-buster-armhf-lite.zip>

## Setup
`sudo apt-get update`  
`sudo apt-get install git `  
`git clone https://www.github.com/basset10/pi_video_looper.git`  
`cd pi_video_looper`  
`sudo ./install.sh`  

Default player is omxplayer. Use the `no_hello_video` flag to install without the hello_video player (a bit faster to install):  
`sudo ./install.sh no_hello_video`

## Updating
Plug in a keyboard and press ESC to access the terminal.    
`cd ~`   
`sudo rm -rf pi_video_looper`   
`git clone https://github.com/basset10/pi_video_looper.git`    
`cd pi_video_looper`   
`sudo ./install.sh` 
