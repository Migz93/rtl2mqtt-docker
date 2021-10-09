# rtl2mqtt-docker
RTL to MQTT

Completed based on https://github.com/mverleun/RTL433-to-mqtt but modified to run on 868mhz

`docker run --name rtl2mqtt-docker -d --privileged -v /opt/rtl2mqtt-docker/config.py:/scripts/config.py -v /dev/bus/usb:/dev/bus/usb miguel1993/rtl2mqtt-docker`