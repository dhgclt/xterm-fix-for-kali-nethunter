how to run as localhost
export DISPLAY=local@host:0
echo $DISPLAY to see if local@host:0 is there now run xterm
how to run as root 
sudo su
export DISPLAY=local@host:0
exit
xhost +local:root
sudo su
now run xterm as root
