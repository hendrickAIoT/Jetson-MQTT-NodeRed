# Jetson-MQTT-NodeRed
IOT using MQTT, Python and Node-Red for Jetson Nano
-----------------------------------------------------
# Tech Stack
## Node Red
## Paho MQTT Python library
## Python3
-------------------------------------------------------
# Installation
### Install Node.js https://nodejs.org/en/download/package-manager
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash - &&\
sudo apt-get install -y nodejs

### Install Node-RED https://nodered.org/docs/getting-started/local
sudo apt-get install npm
sudo npm install -g --unsafe-perm node-red
## run node-red with command
node-red

### Install node-red-dashboard
--------------------------------------------------------------------
# Install MQTT Broker
sudo apt-get install mosquitto mosquitto-clients

# get the Server IP
sudo apt-get install net-tools
ifconfig

# ESP32
### download library PubSubClient and copy to arduino IDE Library Folder
