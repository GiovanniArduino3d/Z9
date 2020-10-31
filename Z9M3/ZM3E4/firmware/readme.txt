Firmware Upload Steps for ZM3Ex:
1. Download the bin file
2. Rename the bin file to firmware.bin
3. Copy firmware.bin to the root directoy of Micro-SD card
4. Power off the printer and plug the Micro-SD card into socket on control board
5. Power on the printer, wait about 30 seconds
===============================================================================

===============================================================================
How to Connect the LCD screen and TFT-LCD screen:
TFT_LCD connect to EXP2 connector (the side one on the board)
LCD12864 connect to EXP1 connector (the side inner on the board)
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
How to Upgrade the 2nd Z axis motor:
Connect the 2nd Motor to the Z2_MOTOR connector
if you didn't use the 2nd Z endstop, keep the Z axis sync belt and don't need to upload firmware, if you used the 2nd Z endstop, remove the Z axis sync belt and upload the firmware with DUALZENDSTOP feature
===============================================================================


===============================================================================
About the firmware name:
Z9M3_ZM3E4_xxx(add features)_V(version)_en(Menu language).bin
===============================================================================



===============================================================================
firmware file description:
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Default firmware for Z9M3
filename: Z9M3_ZM3E4_Vxxxx_en(es/pt/ru/fr).bin
----------------
Control board	: ZM3E4
Exturder     	: Default
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : A4988
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Default for Z9M3_Titan
filename: Z9M3_ZM3E4_TITAN_Vxxxx_en(es/pt/ru/fr).bin
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : A4988
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + TMC220x@XYZ:
Z9M3_ZM3E4_TITAN_TMC220xXYZ_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : TMC2208 or TMC2209 be used to X/Y/Z axis
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + TMC220x@XYZE:
Z9M3_ZM3E4_TITAN_TMC220xXYZE_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : TMC2208 or TMC2209 be used all axis
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + 3D Touch:
Z9M3_ZM3E4_TITAN_3DTouch_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: 3D Touch (BLTouch)
Motor Diver     : A4988
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + TMC220x@XYZE + 3D Touch:
Z9M3_ZM3E4_TITAN_TMC220xXYZE_3DTouch_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: 3D Touch
Motor Diver     : TMC2208 or TMC2209 be used all axis
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + TMC220x@XYZ + DualZ endstops:
Z9M3_ZM3E4_TITAN_TMC220xXYZ_DualZENDSTOP_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : TMC2208 or TMC2209 be used to X/Y/Z axis
Others          : Dual Z ENDSTOPs
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Titan extruder + TMC220x@XYZE + DualZ endstops:
Z9M3_ZM3E4_TITAN_TMC220xXYZE_DualZENDSTOP_Vxxxx_en.bin:
----------------
Control board	: ZM3E4
Exturder     	: Titan 
LCD SCREEN   	: LCD128x64 or/and TFT-LCD
Leveling Sensor	: PL-08N
Motor Diver     : TMC2208 or TMC2209 be used all axis
Others          : Dual Z ENDSTOPs
===============================================================================