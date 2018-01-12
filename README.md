# RadioThermostat-ST
RadioThermostat device handler for SmartThings.

This code is variation of the code published at https://github.com/statusbits/smartthings/blob/master/README.md
Please see that README for details on how to install and configure.
This version incorporates 2 changes:
* Temperature changes made through SmartThngs Routines are implemented as a "permenant" hold on the thermostat instead of a "temporary" hold. This means that the thermostat will no longer follow the programmed schedule until the hold is turned off.
* Sending a target temperature of heating = 0, cooling = 0 will cancel the permanent hold. The thermostat will resume it's schedule. The temp targets of 0,0 are not sent to the thermostat.

Any donations should be sent to the original author at https://github.com/statusbits/smartthings/blob/master/README.md
