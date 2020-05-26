# OctoPrint PSU Control- Orange Pi
Modified to work with Orange Pi One, but will most likley work with other models.

This OctoPrint plugin controls an ATX/AUX power supply to help reduce power consumption and noise when the printer is not in use.

Power supply can be automatically switched on when user specified commands are sent to the printer and/or switched off when idle.

Supports Commands (G-Code or System) or GPIO to switch power supply on/off.

![PSUControl](psucontrol_navbar_settings.png?raw=true)
 
 
## Setup
Install the plugin using Plugin Manager and manual URL input from Settings. https://github.com/mqttnodered/OctoPrint-PSUControl/archive/master.zip

Requires OPi.GPIO package. Install with ~/OctoPrint/venv/bin$ sudo pip install --upgrade OPi.GPIO

Further instructions [API Documentation](https://opi-gpio.readthedocs.io/en/latest/api-documentation.html).

 
## Settings
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Settings)
 
## Troubleshooting
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Troubleshooting)

## API
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/API)

## Support
Help can be found at the [OctoPrint Community Forums](https://community.octoprint.org)

## Feature Requests
[![Feature Requests](https://feathub.com/kantlivelong/OctoPrint-PSUControl?format=svg)](https://feathub.com/kantlivelong/OctoPrint-PSUControl)
