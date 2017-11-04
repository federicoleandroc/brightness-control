# brightness-control
A debian based system tool for brightness controll.

# Install
sudo chmod 666 /sys/class/backlight/acpi_video0/brightness
sudo cp brightness-control /usr/bin/brightness-control

# Usage

"brightness-control h" for help.
"brightness-control x" for set brightness, where x is and integer from 1 to 100.
