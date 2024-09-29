# sirene_NAS-AB01Z
dzvents script for config of neo coolcam NAS-AB01Z via mqtt
Could not find much ionfo on how to do, so now that I have it working I wil share my script
It turned out writing down all the commands separate was the easiest solution as parameters conflicted with the needed single and double quotes
Don't forhet to replace the nodeID with your own nodeID of your siren device in zwave JS UI.

use: 
domoticz.emitEvent('alarm_sirine', '3,1,1,2,8,5,'doorbell','off','off')
domoticz.devices(SireneDevice).switchOn()

Enjoy
