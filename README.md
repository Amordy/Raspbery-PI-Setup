# Raspbery-PI-Setup

format sd
add raspberry op sys

sudo apt-get update
sudo apt-get upgrade

// ip address to the cmdline file
ipv6.disable=1 ip=192.168.0.32

enable ssh


//4.4 kernal role back - not needed if not using carerra
sudo rpi-update 52241088c1da59a359110d39c1875cda56496764

//update to latest node red
update-nodejs-and-nodered


// autostart nodered
sudo systemctrl enable nodered.service
