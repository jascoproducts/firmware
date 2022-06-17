# DISCLAIMER:
The software is provided "as is" to provide our customers the ability to update our products. Jasco does not offer any express or implied warranty of any kind when using these files, including, but not limited to, warranties of merchantability, noninfringement, or fitness for a particular purpose.<br>
<br>
Jasco does not imply or guarantee that the software provided will meet your requirements or that the operation thereof will be uninterrupted or error-free, or that all errors will be corrected. Jasco does not assume any responsibility for product errors related to the use of the software contained within this repository. Jasco does not offer support on flashing firmware to the devices listed here and are only provided as a courtesy to our customers and the community.

## CONTENTS:
ZW4003_Enbrighten-GE_14292_5.20.hex

## RELEASE NOTES:
v5.20: ORIGINAL RELEASE FOR MODEL 14292

## DATE CODES INSTALLED ON:
1651 THROUGH 1741

## CHANGELOG:
1. Original Release Firmware<br>
<br>

## FIRMWARE AVAILABILITY:

At this time, this firmware version will not be made available due to possible hardware compatibility issues that would cause certain hardware variants of this model to fail.

### SUMMARY (TL;DR):

All of the firmware files posted in this repository are not affected by the aforementioned compatibility issue.

We are only omitting firmware files that were built using Z-Wave Devkit 6.51.06 or <b>earlier</b> if that hardware was built with Micron <b>and</b> Adesto variants.

### FULL EXPLANATION:

Z-Wave Plus products are required to use a specific kind of flash memory due to Z-Wave requirements for OTA updates. This memory is uncommon and there are very few supported suppliers.

Abruptly, in 2017, the primary supplier of Z-Wave flash memory, Micron, announced it would discontinue manufacturing this memory. While there were a couple other available suppliers, they were unable to support the volume requirements required for all the current Z-Wave Manufacturers, including Jasco.

Adesto, working with the Z-Wave Alliance, agreed to begin support of this flash memory to fill the volume needs of the Z-Wave Manufacturers. Since the Adesto memory was not previously supported in Z-Wave Devkits, they needed to be added by Z-Wave in a new Devkit release.

Any product that was switching to use Adesto flash would need to update/recompile the firmware to use <i>Z-Wave 500 series 6.51.07 Devkit release or later.</i>

This was an emergency that affected all Z-Wave Plus manufacturers supporting OTA updates, not just Jasco Products.

### IMPORTANT NOTES:

All older products that use the <b>Micron</b> flash <b>can</b> be updated to use the latest firmware OTA files available <b>without issue.</b>

All products made with the <b>Adesto</b> flash <b>cannot</b> be downgraded to a firmware version previously compiled with 6.51.06 or below.

### WHY ARE YOU TELLING ME THIS?

We wanted to be sure we had provided an explanation for why this specific version and other specific versions are not being made available since this was an officially released version.
