# DISCLAIMER:
The software is provided "as is" to provide our customers the ability to update our products. Jasco does not offer any express or implied warranty of any kind when using these files, including, but not limited to, warranties of merchantability, noninfringement, or fitness for a particular purpose.<br>
<br>
Jasco does not imply or guarantee that the software provided will meet your requirements or that the operation thereof will be uninterrupted or error-free, or that all errors will be corrected. Jasco does not assume any responsibility for product errors related to the use of the software contained within this repository. Jasco does not offer support on flashing firmware to the devices listed here and are only provided as a courtesy to our customers and the community.

## CONTENTS:
ZW3104_Jasco_28166_5.21.hex

## Z-WAVE DEVKIT VERSION:
6.51.08

## RELEASE NOTES:
v5.21: SECOND RELEASE FOR MODEL 28166

## DATE CODES INSTALLED ON:
1645 THROUGH PRESENT

## CHANGELOG:
1. Modified the button press process to change the LED status
2. Modified the value to 2 for parameters 8, 10 and 12
3. Modified the asscoation to 3 groups (5 nodes each group)
4. Added Instantaneous reports CC, Scene Activation CC and Scene Actuator CC
5. Modified the button press process for association group 2 and 3
6. Modified the lifeline assocation group, 5 nodes will send singlecast message when the device is reset locally
7. Removed CRC
8. Updated to S-0
9. Modified some command classes to support both security and non-security networks
10. Updated the multilevel command class to version 2
11. Added parameter 6
12. Modified the default status for LED
13. Dimming fix (bKeep) is added for LED light bulb flickering improvement