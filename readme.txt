This python script is a virtual philips hue bridge.
It allows you to control non-hue devices by using the regular philips hue app or anything else that talks the bridge api.

The idea is that htx.py will invoke external programs (e.g. shell scripts) instead of switching on lamps.

Current status: works! You can switch on- and off virtual lights. Also discovery via SSDP/UPNP works but only with the official(!) app - some 3d part software has problems.

required:
- python-configparser
- python-twisted-web


Folkert van Heusden
