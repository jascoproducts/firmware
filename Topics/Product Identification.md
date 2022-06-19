
# Product Identification

<br>

<div align = center>

<img
    src = '../images/Z-Wave%20vs%20Z-Wave%20Plus.png'
    alt = 'Z-Wave vs Z-Wave Plus'
    width = 568
/>
    
</div>

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
    src = '../images/example1.png'
    alt = 'Example of a GE Branded Item'
    width = 350
/>

<img
    src = '../images/example2.png'
    alt = 'Example of an Enbrighten Branded Item'
    width = 350
/>

<br>
<br>

## Folders

The folder structure for firmware is as follows:

`/zwave/<Brand>/<ZW Number>/<Product Number>/<Firmware Version>/<Firmware-File>`

**Example:**

`/zwave/Enbrighten-GE/14288 - In-Wall Smart Outlet/5.26/ZW1002_Enbrighten-GE_14288_5.hex`

Navigate to the correct section based on the <br>
ZW Number and Brand of your device, and <br>
the firmware version you wish to download.

<br>
<br>

## Warning

Downloading and applying the wrong firmware <br>
can cause irreparable damage to your device.

Application of incorrect firmware <br>
will void the warranty on your device.

Please make sure you are getting the correct product, <br>
brand, and version number for your use case.