# INA3221
INA 3221 raspberry pi - wiring pi

to use this program you need to have wiringPi installed on your raspberry pi and I2C bus activated.

apt-get install wiringpi

also modify your device address according to your setup.
to scan for device addess use `i2cdetect -y 1` (1 is the bus number) you may have multiple bus enabled.

to compile use:
gcc ina3221.c -o ina3221 -lwiringPi

Feel free to add comments.
