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
git clone https://github.com/nodesource/distributions.git

cd distribution

sudo apt-get install curl

curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
---------------------------------------------------------------------------------
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
Installing the PubSubClient Library
The PubSubClient library provides a client for doing simple publish/subscribe messaging with a server that supports MQTT (basically allows your ESP32 to talk with Node-RED).
PubSubClinet download link https://github.com/knolleary/pubsubclient

Click here to download the PubSubClient library. You should have a .zip folder in your Downloads folder
Unzip the .zip folder and you should get pubsubclient-master folder
Rename your folder from pubsubclient-master to pubsubclient
Move the pubsubclient folder to your Arduino IDE installation libraries folder
Then, re-open your Arduino IDE
The library comes with a number of example sketches. See File >Examples > PubSubClient within the Arduino IDE software.

Important: PubSubClient is not fully compatible with the ESP32, but the example provided in this tutorial is working very reliably during our tests.


