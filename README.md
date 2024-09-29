# sirene_NAS-AB01Z
Domoticz DzVents script for configuration of shenzhen / neo coolcam NAS-AB01Z via mqtt
Could not find much info on how to do, so now that I have it working, I shared my script
It turned out writing down all the commands separate was the easiest solution as parameters conflicted with the needed single and double quotes
Don't forget to replace the nodeID with your own nodeID of your siren device as seen in zwave JS UI.

Easy to integrate in your doorbell and alarm scripts as you only to have fire an event and turn on the device.

use: 
local SireneDevice = <domoticz device id>
domoticz.emitEvent('alarm_sirine', '3,1,1,2,8,5,'doorbell','off','off')
domoticz.devices(SireneDevice).switchOn()

For all the details of the device see
https://github.com/openhab/org.openhab.binding.zwave/blob/main/doc/shenzhen/nasab01z_0_0.md

Enjoy
