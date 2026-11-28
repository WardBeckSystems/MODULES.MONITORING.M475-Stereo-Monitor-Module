# M475 Stereo Monitor Module · Monitoring

Ward-Beck Systems M475, 1977|10. Wiki page: [M475 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M475.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 42 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 15 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 9 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 124 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 7 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 11 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 41 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [13 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M475 - Monitor Module.pdf](MANUALS/1978%20-%20M475%20-%20Monitor%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Monitor | Solo: 10 dB ±0.5 dB _ 18 dB +0,5 dB |
| **Frequency response** | ±0.25 dB from 30 Hz to 20 kHz. |
| **Noise** | 80 dB be ]ow nomina 1 output of +8 dBm. (20 Hz to 20 KHz). |
| **Harmonic distortion** | Less than 0.357 Thd from 30 Hz to 15 kHz at +24 dBm output or Tess Less than 0.1~ at mid-band at +24 dBm output. |
| **Source impedances** |  |
| &nbsp;&nbsp;Monitor | Solo: 600 ohms or less, balanced/ unbalanced_ 30k ohms; balanced |
| **Input impedances** |  |
| &nbsp;&nbsp;Monitor | Solo: Ta ]kback: 30k ohms; balanced Less than 5 ohms, (summing input)_ 78k ohms; baLanced |
| **Output impedance** | 150 ohms, ba lanced |
| **Load impedance** | 600 ohms, balanced, |
| **Output level** | +8 dBm nominal, +26 dBm maxiMum. |
| **Phasing** | Input and output termina ] s designated by numbers are in phase |
| **Power requirements** | +25 volts dc, 15 mA nomina], 40 ma maximum. |
| **Ambient temperature** | 0 to 60 degrees Celsius. |
| **Dimensions** | 1 6 &quot; wide X 7&quot; high X 6.5&quot; deep. (41 Mm X 178 Mm X 165 mm) |

## Circuit description

From [1978 - M475 - Monitor Module.pdf](MANUALS/1978%20-%20M475%20-%20Monitor%20Module.pdf) pages 6-10 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

M47s MONITOR MODULE The M475 is designed to allow selective access to number of signa ] sources within conso ]e system_ Provision is made for level contro] and muting of the selected signa ] a 5 maybe required The output of the module is intended to drive monitor amplifier a $ well a$ provide headset feed Source selection takes place with the aid of an interlocked five-station push-button assemb Ty. Additionally, the input of the module can be transferred from the five selectab] e inputs to SOLO bus or TALKBAcK input byway of remote contact closure Monitor Inputs Sw1 through Sn5 select any one of five signa] sources which maybe wired to the modu)e inputs 21 22 and their associated components form balanced high input impedance preamplifier. The output of 22 15 coupled through C5 to the MONITOR LEVEL contro] R30 Solo/ Talkback Input Depending on the application of the module, pins 13/P maybe utilized to accept the feed from SOLO bus or alternatively, TALKBACK input maybe connected to pins I1/M_ Both SOLO and TALKBACK inputs are coupled to an isolation summing amplifier consisting of 23 and 24 Following 24 is the SOLO/TB LEVEL contro] R43, a ]owing independent Teve 1 contro] for the SOLO/TB feed Monitor/Solo Switch 25 is solid state swilch which a ]Tows selective gating of either the Monitor or the SOLO/TB input to common output Under norma 1 conditions, 25 will be processing the MONITOR signa ] Connecting pin W of the module connector to ground potential] Will cause 25 to switch to the SOLO/TB signa 1 Output 26 Q1 and Q2 form one-ha ] f of the actively balanced output amplifier with 27, 03 and Q4 Making up the remaining ha ] f Two outputs are provided One is being Picked UP ahead of the muting relay and appears at pins 15/5 The second output i5

**M4Z5 MONITOR_MODUL E**

subject to the operation of the muting relay and is brought out at pins 17/U This output i 5 norma I1y used to feed the associated monitor amplifier Muting Operating the muting relay K1 Will result in reduction of the monitor feed Teve 1 from its nominal +8 dBm output. R77 determines the degree of muting and a ]ows adjustment of the output level from -12 dBm to fully off 05 and 06 function a $ relay driver Muting contro] i5 achieved either by operation of MUTE switch Sw6 or externa]Ty via pin X of the module connector. Power Supply_Decoupl ing C25 through C28 together with R91 and R92 form passive, on-board power supply decoup] ing circuit CRS and CR6 Prevent module damage in the event of accident] polarity reversal

**MFG PART_NUMBER**

C1 C2 C3 c4 C5 Capacitor 4.7 uF/10 V Kemet T3908475M010As 10 pF Philips 2222-638-10109

**33 UF/10 V**

Kemet

**C6 C7 C8 C9 C10**

150 uF/ 6 V T390E157m006AS 2222-638-10109

**10 PF**

Philips

**33 UF/10 V**

Kemet

**T3900336M01OAS**

2.2 uF/25 V 10 uF/25 V T3908225M025AS T390c106m025as

**T390B475M010AS**

0.01 uF delete Aselco cq92-Mc-103m

**C21 C22 C23 C24 C25**

10 pF 220 uF/10 V Philips Kemet

**2222-638-10109 T390F227M010AS**

22 uF/25 Siemens 841313-45226-2

**C26 C27 C28 C29**

10 uF/25 Kemet T390c106m025aS

**CRI CR2 CR3 CR4 CRS**

Diode Motorola Fairchild 1n4003 1n4148 Motorola 184003

**DSI DS2**

LED, red LE 0 ye ] ow Relay Fa irchild

**FLVT1Z FLV410**

Siemens V23012-A0105-4001 Transistor Nationa 1 2n2102 2n4037 2n2897 2n2102 2 0 4 5 06 RI R2 R3 R4 R5

**PN3569**

Resistor #W 5 % 10 10 delete Philips

Philips

**R6 R7 R8 R9 RI 0**

10 delete 10 10 Philips

**RI 1 RI2 RI3 RI4 R15**

delete 10 10 delete PhiliPs

**RI6 RI7 RI8 RI9 R20**

10 10 delete Philips

**R21 R22 R2 3 R2 4 R25**

22k 22k 47k 47k 620 Philips

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclhEbmZFZjVNbDA/view?resourcekey=0-NTUhv95LCa8id1QDysaQnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclhEbmZFZjVNbDA&resourcekey=0-NTUhv95LCa8id1QDysaQnA" width="240" alt="1977 - M475 - front.png"></a><br><sub>1977|10 · front</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbjJ2ZVVYcFduam8/view?resourcekey=0-4WGNkwiVIZT85k61FaQPyg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbjJ2ZVVYcFduam8&resourcekey=0-4WGNkwiVIZT85k61FaQPyg" width="240" alt="1977 - M475 - monitor module 2.jpg"></a><br><sub>1977|10 · monitor module 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0E1ZUpWbG9mSms/view?resourcekey=0-7g8Md0xccf6qzZoWnA0h4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0E1ZUpWbG9mSms&resourcekey=0-7g8Md0xccf6qzZoWnA0h4Q" width="240" alt="1977 - M475 - monitor module.jpg"></a><br><sub>1977|10 · monitor module</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1977|10 · wbsps - module - m475 monitor module 002_small](https://drive.google.com/file/d/0B0yR0b5T78SKOTI2UV81OGpxYVU/view?resourcekey=0-M_iH2La1ZOZIhtNfuhZauw)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjhLWFpqU0UxQUE/view?resourcekey=0-gJad9QhNKIYbfBIeLeKmwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjhLWFpqU0UxQUE&resourcekey=0-gJad9QhNKIYbfBIeLeKmwQ" width="240" alt="1977 - M475 - P13 - Front Panel.jpg"></a><br><sub>1977|10 · P13 - Front Panel · <a href="MECHANICAL/1977%20-%20M475%20-%20P13%20-%20Front%20Panel%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M475.stl`](MECHANICAL/M475.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M475)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 1 6 " wide X 7" high X 6.5" deep. (41 Mm X 178 Mm X 165 mm))
- **From the drawing:** 7 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M475 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M475.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEZMOEEtYzBnaVU/view?resourcekey=0-UtKq59FJ5XE0wDHColaWoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEZMOEEtYzBnaVU&resourcekey=0-UtKq59FJ5XE0wDHColaWoA" width="240" alt="1977 - M475 - 475-02-001 - ALL IC'S LMZOI EXCEPT.jpg"></a><br><sub>1977|10 · 475-02-001 - ALL IC'S LMZOI EXCEPT · <a href="SCHEMATICS/1977%20-%20M475%20-%20475-02-001%20-%20ALL%20IC%27S%20LMZOI%20EXCEPT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1ZFcVl1MHNONW8/view?resourcekey=0-Myrs_UOqYAzaYzuz3Ii7Rg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1ZFcVl1MHNONW8&resourcekey=0-Myrs_UOqYAzaYzuz3Ii7Rg" width="240" alt="1977 - M475 - P16 - Component Layout.jpg"></a><br><sub>1977|10 · P16 - Component Layout · <a href="SCHEMATICS/1977%20-%20M475%20-%20P16%20-%20Component%20Layout%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1qYgtnbWmo2rf7Sy5Zxr-tcHR3j4U60F0/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1qYgtnbWmo2rf7Sy5Zxr-tcHR3j4U60F0" width="240" alt="19xx - M475 - DOC - 475-02-001 - MONITOR MODULE SCHEMATIC.jpg"></a><br><sub>19xx - M475 - DOC - 475-02-001 - MONITOR MODULE SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M475%20-%20DOC%20-%20475-02-001%20-%20MONITOR%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc1B6alFRd3luelk/view?resourcekey=0-WIZd29lASr6tzMmRqWtcXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc1B6alFRd3luelk&resourcekey=0-WIZd29lASr6tzMmRqWtcXg" width="240" alt="1977 - M475 - P17 - Pin Out.jpg"></a><br><sub>1977|10 · P17 - Pin Out · <a href="PINOUTS/1977%20-%20M475%20-%20P17%20-%20Pin%20Out%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | N/C | nc |  | high |
| 2 | MONITOR 5 IN | in | MON 5 IN | high |
| 3 | N/C | nc |  | high |
| 4 | MONITOR 4 IN | in | MON 4 IN | high |
| 5 | N/C | nc |  | high |
| 6 | MONITOR 3 IN | in | MON 3 IN | high |
| 7 | N/C | nc |  | high |
| 8 | MONITOR 2 IN | in | MON 2 IN | high |
| 9 | N/C | nc |  | high |
| 10 | MONITOR 1 IN | in | MON 1 IN | high |
| 11 | TALKBACK IN | in | TB IN | high |
| 12 | N/C | nc |  | high |
| 13 | SOLO IN | in | SOLO IN | high |
| 14 | N/C | nc |  | high |
| 15 | UNMUTED OUTPUT | out | UNMUTED OUTPUT | high |
| 16 | N/C | nc |  | high |
| 17 | MUTED OUTPUT | out | MUTED OUTPUT | high |
| 18 | N/C | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | N/C | nc |  | high |
| B | MONITOR 5 IN | in | MON 5 IN | high |
| C | N/C | nc |  | high |
| D | MONITOR 4 IN | in | MON 4 IN | high |
| E | N/C | nc |  | high |
| F | MONITOR 3 IN | in | MON 3 IN | high |
| H | N/C | nc |  | high |
| J | MONITOR 2 IN | in | MON 2 IN | high |
| K | N/C | nc |  | high |
| L | MONITOR 1 IN | in | MON 1 IN | high |
| M | TALKBACK IN | in | TB IN | high |
| N | N/C | nc |  | high |
| P | SOLO IN | in | SOLO IN | high |
| R | N/C | nc |  | high |
| S | UNMUTED OUTPUT | out | UNMUTED OUTPUT | high |
| T | N/C | nc |  | high |
| U | MUTED OUTPUT | out | MUTED OUTPUT | high |
| V | N/C | nc |  | high |
| W | SOLO/TB CONTROL | control_in | SOLO/TB CTL | high |
| X | MUTE CONTROL | control_in | MUTE CTL | high |
| Y | +24 V | power |  | high |
| Z | CONTROL COMMON | ground |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2s0NXBWSGVqMDA/view?resourcekey=0-La0C5z35992G726g7p3kag" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2s0NXBWSGVqMDA&resourcekey=0-La0C5z35992G726g7p3kag" width="240" alt="1977 - M475 - Monitor Module.pdf"></a><br><sub>1977|10 · Monitor Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWJSOG5adldUbFE/view?resourcekey=0-hkB7gt112f2TReSWhpJh8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWJSOG5adldUbFE&resourcekey=0-hkB7gt112f2TReSWhpJh8w" width="240" alt="1977 - M475 - P01 - Cover.jpg"></a><br><sub>1977|10 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0NWdXBMc3RPUjA/view?resourcekey=0-d_rU7v9N3dKGxuISuVbZJQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0NWdXBMc3RPUjA&resourcekey=0-d_rU7v9N3dKGxuISuVbZJQ" width="240" alt="1977 - M475 - P02.jpg"></a><br><sub>1977|10 · P02</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVW45bkxRWUtUWDg/view?resourcekey=0-yjxHM-ZkmSHEcZX4Rjkotg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVW45bkxRWUtUWDg&resourcekey=0-yjxHM-ZkmSHEcZX4Rjkotg" width="240" alt="1977 - M475 - P04 - Warranty.jpg"></a><br><sub>1977|10 · P04 - Warranty</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ3htVlMwNkNSYzg/view?resourcekey=0-vOiYoDU7aDrqGx9UjC4mGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ3htVlMwNkNSYzg&resourcekey=0-vOiYoDU7aDrqGx9UjC4mGw" width="240" alt="1977 - M475 - P05 - 1-1.jpg"></a><br><sub>1977|10 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVHdJenBpbTlHczg/view?resourcekey=0-SB_pJANw-VOyLlRIBOqGfw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVHdJenBpbTlHczg&resourcekey=0-SB_pJANw-VOyLlRIBOqGfw" width="240" alt="1977 - M475 - P06 - 2-1.jpg"></a><br><sub>1977|10 · P06 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTdiZmk1LXBCQ0U/view?resourcekey=0-dKhxIwoP93-5wkbdxXzTZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTdiZmk1LXBCQ0U&resourcekey=0-dKhxIwoP93-5wkbdxXzTZQ" width="240" alt="1977 - M475 - P07 - 2-2.jpg"></a><br><sub>1977|10 · P07 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWNEajNjeUYwU3M/view?resourcekey=0-rbd9K6XkxQ82sFqPWo-X0w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWNEajNjeUYwU3M&resourcekey=0-rbd9K6XkxQ82sFqPWo-X0w" width="240" alt="1977 - M475 - P08 - 3-1.jpg"></a><br><sub>1977|10 · P08 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVZ4bldHeVRMd28/view?resourcekey=0-yuVEonUfYtxE8PZGra9U5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVZ4bldHeVRMd28&resourcekey=0-yuVEonUfYtxE8PZGra9U5g" width="240" alt="1977 - M475 - P09 - 3-2.jpg"></a><br><sub>1977|10 · P09 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHUxRkJCY3kxQVk/view?resourcekey=0-Pn1w4vDMTKwOaSvISV6YHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHUxRkJCY3kxQVk&resourcekey=0-Pn1w4vDMTKwOaSvISV6YHA" width="240" alt="1977 - M475 - P10 - 3-3.jpg"></a><br><sub>1977|10 · P10 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXZ2QWE0MGZOUm8/view?resourcekey=0-9X4v5sU5uVuHAzIsLS1U7Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXZ2QWE0MGZOUm8&resourcekey=0-9X4v5sU5uVuHAzIsLS1U7Q" width="240" alt="1977 - M475 - P11 - 3-4.jpg"></a><br><sub>1977|10 · P11 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeG9lZjkzYzdJVU0/view?resourcekey=0--lotR57A0ODGyT2vc40K9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeG9lZjkzYzdJVU0&resourcekey=0--lotR57A0ODGyT2vc40K9w" width="240" alt="1977 - M475 - P12 - 3-5.jpg"></a><br><sub>1977|10 · P12 - 3-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZmZjT0pDNVB5VEk/view?resourcekey=0-yIDi67IO3PhTOrmLstx9OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZmZjT0pDNVB5VEk&resourcekey=0-yIDi67IO3PhTOrmLstx9OQ" width="240" alt="1978 - M475 - Monitor Module.pdf"></a><br><sub>1978|11 · Monitor Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRmE1VThvSFgxUGM/view?resourcekey=0-DB4VAHm_uElSa0hycSt0iw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRmE1VThvSFgxUGM&resourcekey=0-DB4VAHm_uElSa0hycSt0iw" width="240" alt="1978 - M475 - P03 - TOC.jpg"></a><br><sub>1978|11 · P03 - TOC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWkhXLWEwUTljVXM/view?resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWkhXLWEwUTljVXM&resourcekey=0-b9n2IVef2O4jjW76Rkhzkg" width="240" alt="19xx - M475 - DOC - L2042 - P04.jpg"></a><br><sub>19xx - M475 - DOC - L2042 - P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdks3aXNVdTdOQkE/view?resourcekey=0-9EY_Jtwlj02gqh9vOxuOww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdks3aXNVdTdOQkE&resourcekey=0-9EY_Jtwlj02gqh9vOxuOww" width="240" alt="19xx - M475 - DOC - L2042 - P09.jpg"></a><br><sub>19xx - M475 - DOC - L2042 - P09</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVEwQzY4bnRleDg/view?resourcekey=0-5_cHg2UP1hCrfQjxzMepcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVEwQzY4bnRleDg&resourcekey=0-5_cHg2UP1hCrfQjxzMepcg" width="240" alt="19xx - M475 - DOC - L2042 - P10.jpg"></a><br><sub>19xx - M475 - DOC - L2042 - P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RnVXFCRU9UeDA/view?resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RnVXFCRU9UeDA&resourcekey=0-HstK7E0Mu-VZp59Y7Wdh1w" width="240" alt="19xx - M475 - DOC - L3242 - P04.jpg"></a><br><sub>19xx - M475 - DOC - L3242 - P04</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVG9HMUgyMUxBRGs/view?resourcekey=0-idNETBR0mGSulBuEaczYvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVG9HMUgyMUxBRGs&resourcekey=0-idNETBR0mGSulBuEaczYvg" width="240" alt="19xx - M475 - DOC - L3242 - P09.jpg"></a><br><sub>19xx - M475 - DOC - L3242 - P09</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanl3MTYxc3RrNkk/view?resourcekey=0-DrZcVip3bpiAYX6ImkrLuQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanl3MTYxc3RrNkk&resourcekey=0-DrZcVip3bpiAYX6ImkrLuQ" width="240" alt="19xx - M475 - DOC - L3242 - P10.jpg"></a><br><sub>19xx - M475 - DOC - L3242 - P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZzU5S3owVE1UdWM/view?resourcekey=0-LPjgcvMP4PiETfpcI_m6lg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZzU5S3owVE1UdWM&resourcekey=0-LPjgcvMP4PiETfpcI_m6lg" width="240" alt="19xx - M475 - DOC - STEREO L SERIES - P005.jpg"></a><br><sub>19xx - M475 - DOC - STEREO L SERIES - P005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2" width="240" alt="19xx - M475 - DOC - WILMA - Aux and main summing.jpg"></a><br><sub>19xx - M475 - DOC - WILMA - Aux and main summing</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - 475-01-001 - MONITOR MODULE FUNCTIONAL DIAGRAM - DRN GEB - ENG RKB - ISS 2.kicad_sch](KICAD/1977%20-%20475-01-001%20-%20MONITOR%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20GEB%20-%20ENG%20RKB%20-%20ISS%202.kicad_sch)
- [1977 - M475 - 475-01-001 - MUTED SOLO SOLOLTB CONTROL MUTE MUTE CONTROL MUTE.kicad_sch](KICAD/1977%20-%20M475%20-%20475-01-001%20-%20MUTED%20SOLO%20SOLOLTB%20CONTROL%20MUTE%20MUTE%20CONTROL%20MUTE.kicad_sch)
- [1977 - M475 - 475-02-001 - ALL IC'S LMZOI EXCEPT.kicad_sch](KICAD/1977%20-%20M475%20-%20475-02-001%20-%20ALL%20IC%27S%20LMZOI%20EXCEPT.kicad_sch)
- [1978 - M475 - Monitor Module p14.kicad_sch](KICAD/1978%20-%20M475%20-%20Monitor%20Module%20p14.kicad_sch)
- [1978 - M475 - Monitor Module p15.kicad_sch](KICAD/1978%20-%20M475%20-%20Monitor%20Module%20p15.kicad_sch)
- [19xx - 475-01-002 - M475A STEREO MONITOR MODULE FUNCTIONAL - ISS 1.kicad_sch](KICAD/19xx%20-%20475-01-002%20-%20M475A%20STEREO%20MONITOR%20MODULE%20FUNCTIONAL%20-%20ISS%201.kicad_sch)
- [19xx - 475-01-002 - STEREO MONITOR MODULE FUNCTIONAL - ISS 1.kicad_sch](KICAD/19xx%20-%20475-01-002%20-%20STEREO%20MONITOR%20MODULE%20FUNCTIONAL%20-%20ISS%201.kicad_sch)
- [19xx - 475-02-002 - STEREO MONITOR MODULE SCHEMATIC - ISS 1.kicad_sch](KICAD/19xx%20-%20475-02-002%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC%20-%20ISS%201.kicad_sch)
- [19xx - M475 - DOC - 475-02-001 - MONITOR MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M475%20-%20DOC%20-%20475-02-001%20-%20MONITOR%20MODULE%20SCHEMATIC.kicad_sch)
- [M475 - P14 - Functional Diagram.kicad_sch](KICAD/M475%20-%20P14%20-%20Functional%20Diagram.kicad_sch)
- [M475.kicad_sym](KICAD/M475.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
