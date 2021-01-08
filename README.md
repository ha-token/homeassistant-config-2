# Se7enair's homeassistant-config

Hello,

this is my HA config. Just want to share it with the world.
The Readme is in English, but the devices and entities are in german.

## How i name my entities?

I use the KISS principle.
keep it short and simple :)

# Devices:
room_device_additive
Example: kitchen_light_sink or floor_light_1stfloor

# Entities from devices:
Use the base from the device and extend it
Example: kitchen_light_sink_brightness or bathroom_temperatursensor_humidity

Sometime I use the additive even if there is for example only one temperature. But most of the time, is is need, because one room contains more than one of the same type of sensor. Example: In livingroom I have 2 climate controls and each of these has a temperature sensor. But I work with a third, external, sensor.
So I need livingroom_climate_left_temperature, livingroom_climate_right_temperature, livingroom_temperaturesensor_temperature.

# Automation:
room_automation
device_automation
It depends on wether the automation is used to control a room, or only a single device
