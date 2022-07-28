# DISCLAIMER:
The software is provided "as is" to provide our customers the ability to update our products. Jasco does not offer any express or implied warranty of any kind when using these files, including, but not limited to, warranties of merchantability, noninfringement, or fitness for a particular purpose.<br>
<br>
Jasco does not imply or guarantee that the software provided will meet your requirements or that the operation thereof will be uninterrupted or error-free, or that all errors will be corrected. Jasco does not assume any responsibility for product errors related to the use of the software contained within this repository. Jasco does not offer support on flashing firmware to the devices listed here and are only provided as a courtesy to our customers and the community.

## CONTENTS:
ZW3008_Jasco_26932_5.32.hex

## Z-WAVE DEVKIT VERSION:
6.51.08

## RELEASE NOTES:
v5.32: SECOND RELEASE FOR MODEL 26932

## DATE CODES INSTALLED ON:
1843 THROUGH PRESENT

## CHANGELOG:
1. Changed device behavior: restart the reset cycle once motion detected (if PIR triggered, 08 sent); if continuous motion detected, the reset cycle will keep being restarted without sending an additional 08; and if no motion detected for a continuous 20s (default), 00 will be sent.
2. Fixed the notification report/GET report issues
3. Fixed AGI issues
4. Modified the operation for factory reset when parameter 19 (alternate exclusion) is set to 1
5. Fixed scene activation issue
6. Fixed an issue to report Lifeline Group 1 if we GET a non-supported group
7. Modified the button press procedure for alternate exclusion and alternate factory reset