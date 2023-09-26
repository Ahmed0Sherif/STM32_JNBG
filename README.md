# Intro
- This repository includes the schematics and PCB design of a double-layer STM32 development Board.
- The code name "JNBG" is in the honour of my group who helped and encouraged me in this project.
- The design is done on KiCAD 6.0
# Components List:
|Component|Quantity|Description| Was Used|
|----|-----|-------|-------|
|STM32f030f4p6|ARM® Cortex®-M0 48MHz FLASH 2.4V ~ 3.6V 32-Bit TSSOP-20 ST Microelectronics|1|Yes|
|AMS1117- 3V3| 3V3 LDO Linear Voltage Regulator  SOT-223-3|1|Yes|
|CH340C|IC Transceiver USB 2.0 2Mbps SOP-16|1|Yes|
|USBLC6-2SC6|ESD Protection TVS Unidirectional Dual Array SOT23-6|1|Yes|
|SMAJ5.0A|Unidirectional TVS 5.0V DO-214AC|1|Not Available|
|Crystal Oscillator|Crystal Oscillator 32MHz 3225|1|Yes|
|LEDs|Green and Red LEDs 0805|1* Green, 1*Red|Yes|
|Ferrite Bead|100Ω @ 100MHz 2.5A 1 100mΩ 0805|1|Yes|
|22uF Capacitor|SMD 22uF 0805|2|Replaced with 1205 Counterpart|
|4.7uF Capacitor|SMD 4.7uF 0603|2|Yes|
|1uF Capacitor|SMD 1uF 0603|2|Yes|
|100n Capacitor|SMD 100nF 0603|1|Yes|
|47nF Capacitor|SMD 47nF 0805|1|Yes|
|10nF Capacitor|SMD 10nF 0603|1|Yes|
|10pF Capacitor|SMD 10pF 0603|2|Yes|
|10k ohm Resistor|SMD 10k 0603|3|Yes|
|1k ohm Resistor|SMD 1k 0603|1|Yes|
|1k5 ohm Resistor|SMD 1k5 0603|3|Yes|
|Tactile Push Button|Micro Push button Switch 2P 3x4x2mm|1|Yes|
|PCB TH SPDT Toggle Switch| Through Hole SPDT Swithc pitch = 2.54mm |1|Yes|
|USB Port|SMD USB-B-Micro |1|Yes|
|Female Headers|TH Female Headers Vertical pitch = 2.54mm|13|Yes|
# SchematicS:
## A-Power Module:
<img src="https://github.com/Ahmed0Sherif/STM32_JNBG/assets/93788514/c162ac07-de76-43d9-88e7-2d57893fa48e" width="50%" height="50%">
 <br>In this circuit, the AMS1117 is used to regulate 5V from USB to 3.3V, with a unidirectional TVS to protect against surges.

# Final Result:
<img src="https://github.com/Ahmed0Sherif/STM32_JNBG/assets/93788514/28036bf6-f4b5-4259-a92d-d2303d070564" width="50%" height="50%">
