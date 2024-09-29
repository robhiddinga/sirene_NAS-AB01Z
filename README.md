# sirene_NAS-AB01Z
dzvents script for config of neo coolcam NAS-AB01Z via mqtt

use: 
domoticz.emitEvent('alarm_sirine', '3,1,1,2,8,5,'doorbell','off','off')
domoticz.devices(SireneDevice).switchOn()
