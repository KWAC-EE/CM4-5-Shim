# CM4-5-Shim
Compatibility layer for RaspberryPi CM4 to be used on CM5-based carriers

<img width="360" height="480" alt="image" src="https://github.com/user-attachments/assets/f49f9bcd-2a2a-41f8-afa7-fa7271bcafa0" />
<img width="664" height="501" alt="image" src="https://github.com/user-attachments/assets/c3ef415f-8804-4b1e-8071-5d4252844900" />
<img width="664" height="501" alt="image" src="https://github.com/user-attachments/assets/55f61fd4-5907-40b7-a968-cb32dc365fbb" />

# Project design files
PCBAs are designed in Altium 22 & 25. This is a paid software platform for professionals, and viewer licenses can be requested from the developers.

# PCBA exports/ Manufacturer files
Designs have been exported as Gerbers with Pick&Place & BOM files such that they may be fully assembled by prototypers such as JLC-PCB, PCB-Way and the like.
Simply upload the zipped project export folder for the PCB, then the internal XLXS/CSV component-level assembly.
Component selection of passives was left generic to allow for flexible sourcing. ICs and other specified parts have a parameter called "LCSC PN", which can be used to preorder components from either LCSC or JLCPCB prior to placing an assembly order.

# Firmware & Software support
Hub is plug&play, and is meant to function with the Raspberry pi CM4 without manual driver installation.
Direct IO is passed from male to female mezzanine headers without modification.

# License
Copyright Kurt Widhalm/@KWAC-EE 2026
This source describes Open Hardware and is licensed under the CERN-OHL-P v2

You may redistribute and modify this documentation and make products using it under the terms of the CERN-OHL-P v2 (https:/cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-P v2 for applicable conditions
