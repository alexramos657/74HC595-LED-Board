# 74HC595 LED Shift Register Board

<h2>Overview</h2>
A custom PCB designed to control eight LEDs using a 74HC595 shift register. This board simplifies expanding digital outputs with minimal microcontroller pins. It features labeled connectors, current-limiting resistors, and clean silkscreen annotations for easy hookup and debugging.

<h2>Features</h2>

- 74HC595 shift register driving 8 LEDs
- Individual resistors for LED current limiting
- Clearly labeled VCC, GND, Data (D), Clock (C), and Latch (L) pins
- Custom silkscreen graphics and logo
- Designed in EasyEDA
- Ordered from JLCPCB (Currently being manufactured, updates coming soon)

<h2>Design</h2>

</p>
<img src="https://i.imgur.com/jaHihYK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<img src="https://i.imgur.com/BQvx1xy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>PCBs Delivered</h2>

<img src="https://i.imgur.com/eFC487j.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

After some waiting, the PCBs arrived and are ready to assemble.

<img src="https://i.imgur.com/7HkdDvI.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/0DL7Tvk.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/JnXnjYF.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Assembly</h2>

<img src="https://i.imgur.com/mH2lP0I.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/lLq1fgv.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/WTXCKfz.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Testing</h2>

The board was connected to an Arduino Uno R3 via five jumper wires:
- D → Arduino digital pin (Serial Data)
- C → Arduino digital pin (Shift Clock)
- L → Arduino digital pin (Latch Clock)
- VCC → 5V
- GND → GND

Using a basic shift register control sketch in the Arduino IDE, the board was tested by cycling through LED patterns. The 74HC595 correctly received serial data and latched output to the LEDs, confirming that the board logic was functioning as expected.

Each LED lit in sequence, confirming:

- All outputs (Q0–Q7) from the 74HC595 are working
- Resistors are limiting current correctly
- Pin labeling and connections matched the intended design

This validates the PCB as a reliable LED driver module, and it's now ready for use in future Arduino or embedded projects.

<img src="https://i.imgur.com/9DvzgXa.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Xn3aEui.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
