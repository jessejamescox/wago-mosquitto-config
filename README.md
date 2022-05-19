# wago-mosquitto-config
Sample config to run mosquitto MQTT broker on WAGO Device


Run mosquitto on WAGO device in Docker with the following command:

`docker run -it -p 1883:1883 -v /mosquitto/mosquitto.conf:/mosquitto/config/mosquitto.conf --restart unless-stopped eclipse-mosquitto:2.0.11`
