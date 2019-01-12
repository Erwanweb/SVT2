# SmartVirtualThermostat for ON/OFF Heaters with presence detection
Smart Virtual Thermostat python plugin for Domoticz home automation system

install :

cd ~/domoticz/plugins 

mkdir SVT2

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/SVT2.git SVT2

cd SVT2

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/SVT2

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart
