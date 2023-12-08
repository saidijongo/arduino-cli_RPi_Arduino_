# arduino-cli_RPi_Arduino_
Trying to access access and upload arduino programs remotely via a raspberry pi

arduino-cli board list
sudo arduino-cli core install arduino:mbed_nano
arduino-cli compile --fqbn arduino:mbed_nano:nanorp2040connect
arduino-cli compile --upload -p /dev/ttyACM0 -b arduino:mbed_nano:nanorp2040connect



