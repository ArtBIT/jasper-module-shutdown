# Jasper-Module-Shutdown

Shutdown your RaspberryPI using your voice.

Jasper Shutdown Module for my [HAL9000 Raspberry PI Instructable](http://www.instructables.com/id/RaspberryPI-HAL9000/)

Written By: Djordje Ungar

## Steps to install Shutdown Module

* run the following commands in order:
```
git clone https://github.com/ArtBIT/jasper-module-shutdown.git
cp jasper-module-shutdown/Shutdown.py <path to jasper/client/modules>
#i.e. cp jasper-module-shutdown/Shutdown.py /usr/local/lib/jasper/client/modules/
```
* Restart the Pi:
```
sudo shutdown
```
## Congrats, JASPER Shutdown Module is now installed and ready for use
Here are some examples:
```
YOU: Shutdown
JASPER: *says a witty remark and shuts-down*
```

