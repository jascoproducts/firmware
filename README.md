
# Jasco Firmware

*Jasco Products Company LLC*

<br>

<div align = center>

---

[![Button Identification]][Identification]   
[![Button Finding]][Finding]   
[![Button Updating]][Updating]

---

<br>
<br>

## Content

The [`/zwave/`][ZWave] directory contains all <br>
currently available Z-Wave Firmware.

These files have been tested and validated <br>
by the **Jasco Connected Home** team.

*As testing occurs additional files will be released.*

<br>

### Missing Items

If your item is not currently on this list, you <br>
can open a **[Firmware Request]** and we will <br>
move it up on our priority list to release.

<br>

### Reporting Bugs

If you wish to report a problem with a particular <br>
Firmware version, please open a **[Bug Report]** <br>
and we will investigate at the earliest opportunity.

<br>
<br>

## Release Schedule

We will be working through and validating <br>
all current products that are capable of OTA <br>
updates and releasing them each Friday.

*Once all current products have been listed* <br>
*we will reevaluate the schedule as necessary.*

***Zigbee*** *firmware coming soon.*

<br>
<br>

# Ｄｉｓｃｌａｉｍｅｒ

```

The software is provided "as is" to provide our
customers the ability to update our products.

Jasco does not offer any express or implied
warranty of any kind when using these files,
including, but not limited to, warranties of
merchantability, noninfringement, or fitness
for a particular purpose. 

Jasco does not imply or guarantee that the
software provided will meet your requirements
or that the operation thereof will be
uninterrupted or error-free, or that all
errors will be corrected.

Jasco does not assume any responsibility for
product errors related to the use of the
software contained within this repository.

Jasco does not offer support on flashing firmware
to the devices listed here and are only provided
as a courtesy to our customers and the community.

```

</div>

<br>
<br>
<br>

<a name = 'product-identification'></a>

<br>

<div align = center>

# Ｐｒｏｄｕｃｔ　Ｉｄｅｎｔｉｆｉｃａｔｉｏｎ

***Find out what type product you own.***

<br>
<br>

<img
    src = './images/Z-Wave%20vs%20Z-Wave%20Plus.png'
    alt = 'Z-Wave vs Z-Wave Plus'
    width = 568
/>
    
</div>

<br>
<br>

## Steps

<br>

1. **Identify the Product Brand.**

    This can be found in the upper left corner and will say one of the following brands:

    - <kbd> <br> Enbrighten-GE <br> </kbd>
    - <kbd> <br> Honeywell <br> </kbd>
    - <kbd> <br> UltraPro <br> </kbd>
    
    <br>

2. **Identify your ZW Number.**

    This can be found on the device itself, <br>
    typically on the upper corner or back <br>
    of the product itself.

    <br>

3. **Identify your Product Number.**

    These are typically on the back of the <br>
    device in question followed by `-x`
    
    #### Example
    
    `46201-2` or `55256-1`

    #### Note

    These will not be 5 digits next to `PIN:`.
    
    The Pin number is for Z-Wave S2 Security inclusion.


<br>
<br>

## Examples

<img
    src = './images/example1.png'
    alt = 'Example of a GE Branded Item'
    width = 350
/>

<img
    src = './images/example2.png'
    alt = 'Example of an Enbrighten Branded Item'
    width = 350
/>

<br>
<br>

## Folders

The folder structure for firmware is as follows:

`/zwave/<Brand>/<ZW Number>/<Product Number>/<Firmware Version>/<Firmware-File>`

**Example:**

`/zwave/Enbrighten-GE/14288 - In-Wall Smart Outlet/5.26/ZW1002_Enbrighten-GE_14288_5.26.hex`

Navigate to the correct section based on the <br>
ZW Number and Brand of your device, and <br>
the firmware version you wish to download.

<br>
<br>

## Warning

```
Downloading and applying the wrong firmware
can cause irreparable damage to your device.

Application of incorrect firmware will
void the warranty on your device.

Please make sure you are getting the correct product,
brand, and version number for your use case.
```

<br>
<br>
<br>

<a name = 'finding-firmware'></a>

<br>

<div align = center>

# Ｆｉｎｄｉｎｇ　Ｆｉｒｍｗａｒｅ

***Search for the firmware your device needs.***

</div>

<br>
<br>

## Search

*You can find the search page by clicking the  **<kbd>  [Go to file]  </kbd>**  button.*

[<img
    src = './images/Finding Firmware/Goto.png'
    alt = 'Where you can find the button for the search page.'
    width = 600
/>][Go to file]

<br>
<br>

## Z-Wave

*You can use your **Z-Wave Number** to search.*

[<img
    src = './images/Finding Firmware/Z-Wave.png'
    alt = 'Example of searching for a Z-Wave Number.'
    width = 600
/>][Go to file]

<br>
<br>

## Model

*You can use your **Model Number** to search.*

[<img
    src = './images/Finding Firmware/Model.png'
    alt = 'Example of searching for a Model Number.'
    width = 600
/>][Go to file]

<br>
<br>
<br>


<a name = 'firmware-updates'></a>

<br>

<div align = center>

# Ｆｉｒｍｗａｒｅ　Ｕｐｄａｔｅｓ

***Update the firmware on your device.***

</div>

<br>
<br>

## WiFi

WiFi products currently require the <br>
use of our app to update the firmware.

<br>
<br>

## Home Assistant

Home Assistant will automatically inform you when updates for your device are available.

<br>
<br>

## Hubs

The exact instructions on how to update your firmware <br>
differ depending on the hub / system you are using.

*Please review the documentation provided by* <br>
*support staff of the hub / system in question.*

<br>

### Note

Some hubs / systems currently do not offer **OTA** updates, <br>
and any requests to add functionality to do so should be <br>
directed to the support for those specific systems.

<br>
<br>

<!--
    
    Hey cool, you read the comments and code. 
    Since you found this, have a discount on us. 
    Use LINUS10 for 10% off your next order on
    (https://byjasco.com).
    

    *Offer valid for purchase and shipment in 
    the U.S. only when redeemed by 7/31/2022. 
    
    Coupon code is required, discount will 
    be applied when you enter the coupon 
    code during the shopping cart process 
    (case-sensitive).
    
    Coupon codes may only be redeemed once.
    
    Sales tax and shipping excluded.
    
    Dealers, distributors and other re-sellers 
    are not eligible for this offer.
    
    Additional terms, conditions, products, 
    pricing and offers subject to change 
    without notice.
    
    Cannot be used on already discounted
    items or combined with other offers.
    
    Not redeemable for cash or valid
    toward previous purchases.
    
    Price match refunds are not eligible 
    with any other promotions.
    
    Free Shipping is valid in the U.S. only
    for purchases of $50 or more in same order.
    
    If you choose another shipping option,
    additional charges will apply.
    
-->


<!----------------------------------------------------------------------------->

[Identification]: #product-identification 'How to determine what type of product you own.'
[Updating]: #firmware-updates 'How to update the firmware on your device.'
[Finding]: #finding-firmware 'How to find the firmware for your device.'

[Firmware Request]: https://github.com/jascoproducts/firmware/issues/new?assignees=&labels=&template=firmware_request.yml&title=%5BFirmware+Request%5D%3A+BRAND+-+ZW+NUMBER+-+PRODUCT+NUMBER
[Bug Report]: https://github.com/jascoproducts/firmware/issues/new?assignees=&labels=&template=bug_report.yml&title=%5BBug+Report%5D%3A+BRAND+-+ZW+NUMBER+-+PRODUCT+NUMBER+-+FW+VERSION
[Go to file]: https://github.com/jascoproducts/firmware/find/main
[Addon_ZWaveJS2MQTT]: https://my.home-assistant.io/redirect/supervisor_addon/?addon=a0d7b954_zwavejs2mqtt 'Open this add-on in your Home Assistant instance.'
[Addon_ZwaveJS]: https://my.home-assistant.io/redirect/config_flow_start?domain=zwave_js 'Open this add-on in your Home Assistant instance.'
[ZWaveJS2MQTT]: https://zwave-js.github.io/zwavejs2mqtt/
[ZWaveJS]: https://www.home-assistant.io/integrations/zwave_js/

[License]: #
[ZWave]: zwave


<!--------------------------------[ Buttons ]---------------------------------->

[Button Identification]: https://img.shields.io/badge/Product_Identification-00A0DF?style=for-the-badge&logoColor=white&logo=GitBook
[Button Updating]: https://img.shields.io/badge/Updating_Firmware-ED145B?style=for-the-badge&logoColor=white&logo=RSS
[Button Finding]: https://img.shields.io/badge/Finding_Firmware-37a779?style=for-the-badge&logoColor=white&logo=OpenStreetMap
[Button Addon]: https://my.home-assistant.io/badges/supervisor_addon.svg

