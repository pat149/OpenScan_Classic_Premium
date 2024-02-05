# OpenScan Classic Premium
Completely redesigned version of the OpenScan Classic by Thomas Megel ([ @github/OpenScan-org ](https://github.com/OpenScan-org)).

> [!CAUTION]
> This version is still work in progress and early access. There's no guarantee everything works as intended.

![OpenScan Classic Premium](/pictures/OpenScan.PNG)

## Introduction
The intentions behind the redesign of the OpenScan Classic were that it seems it has never gotten out of it's prototype stage constructionwise.
So I made a list with things that should be improved.

- sturdier overall construction
- more convenient height adjustment
- use ball bearings instead of pins
- use heated inserts instead of driving the screw into the plastic
- higher modularity concerning the size of the scanner
- cable management for the turntable stepper
- printing without any supports

So I redesigned the Classic version from scratch on and the result was the OpenScan Classic Premium (might change the name in the future). No parts of the original mainframe have been reused in order to make room for improvements while simultaneously keeping the original shape and functionality.
Because I don't use a PiCam I didn't redesigned the stand for the Raspberry Pi (yet).

## Bill of material
This BOM represents the bare minimum of material without using any extensions on the arms.
| Part  | Quantity |
| ------------- | ------------- |
| M3x8 (ISO 4762) | 8  |
| M3x10 (ISO 4762) | 2  |
| M3x25 (ISO 4762) | 2  |
| M3x30 (ISO 4762) | 4  |
| M5x20 (ISO 4762) | 1  |
| M5x25 or M5x30 (ISO 4762) (depending on shaft stick out) | 1  |
| Washer M5  | 2  |
| Heated Insert M3x4  | 8  |
| Heated Insert M5x6  | 2  |
| Ball bearing 625-2RS  | 4  |
| Nema 17 Stepper Motor (>13Ncm)  | 1  |
| Nema 17 Stepper Motor (>40Ncm)  | 1  |
| Stand1_Nema17.step  | 1  |
| Stand2.step  | 1  |
| Spacer_Adapter_Gear.step (Measure shaft stick out for correct version)  | 1  |
| Gear_Small.step  | 1  |
| Adapter_Gear.step  | 1  |
| Adapter.step  | 1  |
| Rotary_Arm.step  | 2  |
| Turntable_Base1.step  | 1  |
| Turntable_Base2.step  | 1  |

## Print settings
Every printed part can be printed without any supports at all using the following print settings:
- 0.4mm nozzle
- 0.2mm layer height
- 3 walls (except for Turntable_Base, Turntable_Extension and Rotary_Arm: min. 5 walls, depending on the overall length)
- 15% infill

## Assembly instructions
> [!NOTE]
> Coming soon!

![Assembly of the motor stand](/pictures/Stand1_Nema17_Exploded.PNG)
![Assembly of the stand 2](/pictures/Stand2_Exploded.PNG)
![Assembly of the arms](/pictures/Arms_Exploded.PNG)

## To-do-list
- [ ] Adding more rigidity to the turntable stepper frame mount
