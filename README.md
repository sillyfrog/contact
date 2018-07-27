# Contact Me and Useful Links
Not a real repo, but if you want to ask me a question I may be able to help with, just log an issue here. That way others can see the answers as well.

Below are some links and sources of things that I have found useful for getting me going with home automation.

## Andreas Spiess - YouTube
Andreas has some great run throughs of various bits of hardware, and goes through the pro's and con's of of the bit and bobs he's interested in: https://www.youtube.com/channel/UCu7_D0o48KbfhpEohoP7YSQ

## Mosquito
This is the central server I use for connecting all my things. Built on MQTT, I found that there are adaptors for most things to connect to MQTT: https://mosquitto.org/

When building an automation system, I found this to be the central "hub" for everything after experimenting with several things.

## openHAB
An automation platform, with apps for various devices, and a great way to get a UI on top of things. A fairly steep learning curve, but a heap of integrations for many different things. I started with this as the central server over MQTT, however found MQTT easier in the end, and connect openHAB to MQTT for integration with the various devices. This means a bit of double handling, but it works for me.

https://www.openhab.org/

## HomeKit to MQTT bridge
How I connect my Apple HomeKit to everything. Using the HomeKit to MQTT bridge I can ask Siri to "open the blinds" etc. I would recommend running this is Docker if it's an option in your environment as there are a bunch of dependancies. https://github.com/hobbyquaker/homekit2mqtt

