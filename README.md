# homeassistant
Home Assistant Config examples

Using Home Assistant to control the (AU) Daikin SkyFi Aircon Unit

I've configured SkyFi (only temperature readings and On/Off) and also enabled the Alexa listener for on/off commands.

Despite the communication issues with SkyFi, it works most of the time, and best of all, if you expose Home Assistant externally, you can control from outside of your LAN.

Here are the Home Assistant configs segments I am using.
Obviously replace the IP address and Skyfi Password with your own!
The Alexa listener IP is the IP address of your Home Assistant Server

With this config I can use Home Assistant UI to turn Aircon on and off, as well as monitor state and internal/external temps. Also, with some work on the curl commands, you could render all of the other response codes documented above.
