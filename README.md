# docker-rtl433-mqtt
RTL433 to MQTT

Completed based on https://github.com/mverleun/RTL433-to-mqtt but modified to run on 868mhz

`docker run --name rtl_433 -d --privileged -v /dev/bus/usb:/dev/bus/usb miguel1993/docker-rtl433-mqtt`