# Turbo Duo DIN 8 90 Degree
The PC Engine Duo / Turbo Duo DIN 8 AV port protrudes out the side, an inconvenience in some setups. This two piece PCB assembly is designed to rotate the DIN 8 connector 90 degrees to face towards the rear.

There are two styles, lower (3E-300009) and lower (3E-300010). Each style can be configured for either input or output using solder jumpers and the proper components.

The Turbo Duo uses a DIN 270 connector, which if modded for RGB video will typically use a DIN 8 270 connector. However, PCB 180 mount DIN 8 270 male connectors are unavailable at this time, so this board was designed to accept both DIN 8 262 and 270 male connectors.

Therefore, I would recommend replacing the PCB 90 mount DIN 8 female connector on your Turbo Tuo with a DIN 8 270 connector if using this device.

The lower board includes an optional sync stripper for CSYNC output.


![BNCtoSCART](photos/DSC_8581.jpg)

## Files Included
- **PCB Design Files** (KiCAD, Gerber)
- **Bill of Materials** (XLSX)
- **CAD** (STEP)
- **Photos**

## Assembly
1. Solder all components in place. Alternatively if sync stripper is not used solder jumper JP1.
2. Solder upper board to lower board.
3. Both: Solder J4-6 in place. P1-2 may be soldered in place as mounting posts for the SCART-Lock.
2. Close solder jumpers JP1-3 appropriately for either input or output type.

## PCB Revision History
- Rev 1 - Initial release
- Rev 0 - Development (unreleased)

## License
This project is open-source under the [CC BY 4.0 (Attribution 4.0 International)](https://creativecommons.org/licenses/by/4.0/).

## Disclaimer
This project is provided "as-is" without any warranty, express or implied, including but not limited to warranties of merchantability or fitness for a particular purpose. No support is provided.

Amazon links are affiliates.