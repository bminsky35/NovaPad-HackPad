# NovaPad three-button PCB

This KiCad board is a starting point for a three-button macro pad. It has three
through-hole 6 mm tactile-switch footprints and a 1x4 header for an external
controller; it does not include a microcontroller, USB connector, or firmware.

Open `NovaPad.kicad_pcb` in KiCad. The header pins, from pin 1 to pin 4, are:

| Pin | Connection |
| --- | --- |
| 1 | GND |
| 2 | SW1 |
| 3 | SW2 |
| 4 | SW3 |

Each switch connects its signal to GND when pressed. Provide pull-ups at the
controller inputs. The board uses a generic 6 mm tactile-switch footprint;
confirm the switch's pin spacing and body clearance against the part you choose
before fabrication. The header footprint is a standard 2.54 mm-pitch vertical
1x4 pin header.
