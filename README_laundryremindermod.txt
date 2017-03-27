Please read the README.md for a full description
This readme only adds information for the laundry improvement

Edit /etc/rc.local to make the program run when the device boots up.

Add before the exit line:

python /home/pi/laundry.py /home/pi/laundry_settings.ini &

