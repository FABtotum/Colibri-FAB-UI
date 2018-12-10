![N|Solid](http://www.fabtotum.com/fabui_v1.png)

The FABUI (FABtotum User Interface) Colibri is the first Operating System completely developed by the Team to control all the FABtotum Personal Fabricator functionalities, including 3D printing, Milling, Engraving, Network Management, Diagnostic and File Management.

More than a 3D printing software, it is preinstalled onboard: this means no download and no required space on your computer. Just run the first setup and in a minute you’ll be ready.
Once it is connected to the WiFi there is no need to be phisically linked to the FABtotum!

## Installation
  - Download the latest archive [here][latest-archive]
  - Use at least 4GB SD Card
  - [Format an SD Card](https://github.com/FABtotum/fabui-colibri/wiki/SDCard-formatting) to one FAT32 with label “boot”
  - Unzip the file you downloaded at step 1 and copy all files to Sd Card
  - Insert the SD Card into the slot of the FABtotum
  - Connect to the FABtotum via Ethernet cable
  - Turn on the FABtotum
  - Wait for the leds to became blue and open a web browser and in the address bar type 169.254.1.2
  
  **See the [Wiki](https://github.com/FABtotum/fabui-colibri/wiki) for more docs.**

## What's new
  - New OS from scratch
  - Designed to be more resilient to power failures
  - No SD Card flashing needed, only simple copy
  - Earlyboot-WebUI for first install and recovery
  - Built-in recovery procedure
  -- Recovery can preserve user and system settings
  - Faster boot, install and recovery
  - Http server Apache 2 replaced by Lighttpd
  - Application database MySQL replaced by SQLite 3
  - Upgraded to Codeigniter framework 3.x
  - Full backend redesign
  - Uses WebSocket and XML-RPC for faster UI vs backend communication
  - UI pages loaded via ajax for faster navigation and better user experience
  - Easy to write python script extensions
  - New Plugin framework that allows better plugin integration into the UI
  - Added standard views to help write plugin UI easier
  - Plugin generator for easy plugin creating
  - Plugins can extend supported file types and integrate into Project manager
  - Plugin online repository
  - All system updates accessible from Update section
  - Firmware rollback to previous versions
  - On RPi3 wifi Access Point mode is supported
  - Custom head settings creation (Thermistor, PID, capabilities..)
  - Probe length store per head so no recalibration is needed when heads are switched
  - Jog redesigned
  - Jog supports multiplier for easier step change on touch interfaces
  - Jog supports bed touch interface for fast head positioning
  - Built-in GCode help that is in sync with the current firmware
  - GCode help supports search by code and description
  - Milling and laser engraving jog support position storing/restoring, useful for multi-step manufacturing or laser height calibration

## Support & Contributing
Please [open an issue](https://github.com/FABtotum/fabui-colibri/issues/new) for support
   
   [latest-archive]: <https://github.com/FABtotum/fabui-colibri/releases/download/1.1.6/fabui_1.1.6.zip>
