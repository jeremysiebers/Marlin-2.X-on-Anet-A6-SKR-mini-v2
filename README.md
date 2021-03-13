# Marlin-2.X-on-Anet-A6-SKR-mini-v2
ANET A6 3D printer running Marlin 2.x on Bigtreetech SKR mini V2

Changed pins_BTT_SKR_MINI_E3_common.h to be compatible with ANET A6 LCD screen.
Swap of 5V and GND wires required between SKR mini V2 EXP connector and LCD screen.
Changed entry in pins_BTT_SKR_MINI_E3_common.h is CR10_STOCKDISPLAY.

Delta to original ANET A6:
BLTouch sensor
Bondtech BMG (415 steps/mm)
E3d V6 1.75mm 12V bowden hotend (#TEMP_SENSOR_N 5)

Marlin config:
BL Touch
Gantry (up-wards end of stroke) levelling (G34)
Billinear bed levelling (G29)