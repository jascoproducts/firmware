# Welcome to the Jasco Products Company LLC (Jasco) Firmware Repository! 

# Disclaimer

The software is provided "as is" to provide our customers the ability to update our products. Jasco does not offer any express or implied warranty of any kind when using these files, including, but not limited to, warranties of merchantability, noninfringement, or fitness for a particular purpose. 

Jasco does not imply or guarantee that the software provided will meet your requirements or that the operation thereof will be uninterrupted or error-free, or that all errors will be corrected. Jasco does not assume any responsibility for product errors related to the use of the software contained within this repository. Jasco does not offer support on flashing firmware to the devices listed here and are only provided as a courtesy to our customers and the community. 

# Files Contained In This Repository

Z-Wave Firmware is avaliable for items listed in the following document - [ZWave Product Firmware Listing](docs/listing.txt)

If your item is not currently on this list, please open an [Issue](https://github.com/jascoproducts/firmware/issues/new) to request the files.

Wifi products currently require the use of our app to update the firmware. If you have an Enbrighten, Jasco Pro, MyTouchSmart, or other Jasco branded device, please use the appropriate app to deploy the latest firmware to your device. 

Zigbee Firmware is currently unavalibile. We are actively looking to provide these to our customers at a later date.

# Identifying Your Product

First - Identify your ZW Number. This can be found on the device itself, typically on the upper corner or back of the product itself.

Second - Identify the Product Brand. This can be found in the upper left corner and will say one of the following brands:

GE
Enbrighten
Honeywell
Ultra Pro

Example pictues are below:

[<img alt="Example of a GE Branded Item" width="350px" src="images/example1.png" />]

[<img alt="Example of an Enbrighten Branded Item" width="350px" src="images/example2.png" />]

The folder structure for firmware is as follows:

Root - ZWAVE - (ZW Number) - (Brand) - (Version Number) - Firmware File

Navigate to the correct section based on the ZW Number and Brand of your device, and the firmware version you wish to download.

PLEASE NOTE: Downloading and applying the wrong firmware can cause irreperable damage to your device. Application of incorrect firmware will void the warranty on your device. Please make sure you are getting the correct product, brand, and version number for your use case.

# Updating Your Firmware

For exact instructions on how to update your firmware, please review the documentation outlining this process for your specific home automation hub/system. Documentation must be provided by the support staff for the home automation hub/system in question. Some hubs and systems do not currently offer OTA updates, and any requested functionality to do so should be directed to the support for those specific systems.

Updates via HomeAssistant require the [ZWaveJS2MQTT addon](https://github.com/hassio-addons/addon-zwavejs2mqtt/blob/main/zwavejs2mqtt/DOCS.md).

[![Open this add-on in your Home Assistant instance.][addon-badge]][addon]


[addon-badge]: https://my.home-assistant.io/badges/supervisor_addon.svg
[addon]: https://my.home-assistant.io/redirect/supervisor_addon/?addon=a0d7b954_zwavejs2mqtt
