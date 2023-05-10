# Kali-linux-Macbook-pro-2013-fan-controller


A very basic script i made to be able to change my fanspeed on macbook pro running kali linux
All the script does is reading the user input and echoes it to the applesmc located at /sys/module/applesmc/drivers/platform:applesmc/applesmc.768/fan1_min



To use the script extract the fanspeed file to /usr/bin or /bin/
The script must be executed with sudo or root.

The script is only tested on macbookpro mid 2013. It should work on any macbook with applesmc.768

As of now it's just a simple script but will make it fancier later

