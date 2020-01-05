# Home Assistant Setup 

Where I back up and document my HA setup at home 🏠⚡️  
I've recently moved to Hass.io, and I run it as a VM through Proxmox.  

![Screenshot of the main page](https://raw.githubusercontent.com/dahlmo/homeassistant-home/master/img/screenshot1.png)  

## Hardware used to run HA 
🖲 Intel NUC NUC6CAYH w/4GB RAM and 120GB SSD  
– Virtualized with Proxmox  
–– Runs Hassos supervisor which in turn runs Hass.io 🐳  
🍒 Raspberry Pi3 w/touchscreen  
– Acts as a handy dashboard in our hallway  
– Sends Bluetooth signals over MQTT to HA  
⚡️ Aeotec Z-Stick Gen 5 for Z-Wave  

## Integrations 
🧹 [Xiaomi Roborock S55 Vacuum](https://www.home-assistant.io/integrations/vacuum.xiaomi_miio/) keeps the floors clean  
💡 [IKEA Trådfri](https://www.home-assistant.io/integrations/tradfri) controls the ceiling lights in living- and dining room  
🚨 [Verisure](https://www.home-assistant.io/integrations/verisure) allows controlling the locks of the apt. door  
🏡 [HACS](https://github.com/hacs/integration) enables easier installation of custom components  
🔴 [Node Red](https://nodered.org/) gives opportunity of defining automations as visualized flows  
🔵 [Monitor](https://github.com/andrewjfreyer/monitor) genius passive BT presence detection over MQTT  

## Custom components
- [Volkswagen Carnet](https://github.com/robinostlund/volkswagencarnet) displays vehicle information  

## Lovelace components
- [Xiaomi Vacuum Map Card](https://github.com/PiotrMachowski/lovelace-xiaomi-vacuum-map-card)  
- [Mini Media Player](https://github.com/kalkih/mini-media-player)  

## 🗺 Roadmap
~~– MQTT to relay Bluetooth from Rpi3~~  
– ESP8266 to control apartment complex intercom  

## Some things to note
Some files are gitignored on purpose, for example secrets.yaml (obviously) and vw_vins.yaml.  