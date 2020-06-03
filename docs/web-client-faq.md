Web Client Support

# How does the Web Client work?
The device that is running the game act's as a server for your players to connect to, either locally or over the internet. You can access this option by subscribing to Encounter Plus and accessing the External Display setting located in the top left of Encounter Plus and turn it on. This feature will be included when it is out of beta.

### Why doesn’t the URL Encounter Plus gives me work?
**There are two parts to this question.**
1. Part one: you need to **open port 8080 on your router** for the IP address Encounter Plus is displaying. That needs to be done on your router. **Please refer to your routers user manual** or https://portforward.com for information on how to change port settings.
2. Part two: The IP address that is given to you within Encounter Plus is just the devices IP address. @rrgeorge has provided a tool to assist you with identifying your externally facing IP address if the one provided does not work. https://w.bobg.us/e.php

### I opened the port and got my IP address, but it still says Websocket Disconnected when players try to join.
This can happen when **browsers automatically redirect to https://client.encounter.plus instead of http://client.encounter.plus.** Try turning on **incognito mode in Chrome or Private Browsing in Safari** to keep it from redirecting. If your browser is still redirecting to https, **try clearing your browser history.** 

**Note: Currently, only Safari and Chrome have been tested for the Encounter Plus Web Client.** 

### All or some of my tokens aren't appearing on the web client.
**Try moving the tokens around to refresh them** on the web client side. If that doens't work, **try turning off web server in Encounter Plus and turning it back on.** Once this is done **have the players reconnect.** 

### What are the different settings in the web server section of Encounter Plus?
Those allow the DM to control how many people can interact with the tokens onscreen at any given point. 
- **All** Anyone can move tokens at anytime. 
- **Turn Only** Anyone can move a token when it is that tokens turn on initiative order.
- **None** No player can move tokens. 

### Known Issues
- There is no way to remove access from the server. Be mindful when sharing your IP.
- Tokens controlled in the webview have the ability to move through walls, unless you enable restricted movement as the DM ![Restricted Movement Icon](https://help.encounter.plus/icons/move-restricted2.png "Restricted Movement"), so be careful when moving them. 
- Auras and other animated assets are not yet available. 
- All writing with the pen or highlighter tool will be visible, regardless of the layer.

