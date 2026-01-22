# Digital Diya (Sound + Light Activated LED) using ATtiny85 – PCB Designed in KiCad 9.0

📖 Project Description
This project is a Digital Diya designed using KiCad 9.0, which works like a smart diya/light.
It uses:
LDR07 to detect light/dark conditions
Condenser Microphone to detect sound (like clap/blow)
ATtiny85-10P as the controller
LED as the output glowing diya light
Battery cell for portable power
SPDT switch for ON/OFF control
The circuit is designed as a compact PCB layout in KiCad 9.0, suitable for mini DIY electronics projects.

🧩 Components Used (BOM)
Component	Quantity	Description
ATtiny85-10P	1	8-bit Microcontroller
LED	1	Output Diya Light
Resistor	2-3	For LED + Sensor biasing
Condenser Microphone	1	Sound input sensor
LDR07	1	Light dependent resistor
Battery Cell	1	Power source
SPDT Switch	1	ON/OFF control
3.3V Supply	1	Power rail
GND	1	Ground reference

⚙️ Working Principle
✅ Light sensing (LDR07)
When it is dark, the LDR resistance increases → ATtiny85 detects low light and allows the diya to glow.
✅ Sound sensing (Microphone)
The microphone detects sudden sound (clap / blow / noise pulse) and sends signal to ATtiny85.
Based on programming logic, ATtiny85 can toggle or control LED brightness.
✅ LED Output
LED turns ON like a diya and glows depending on conditions.
✅ Switch Control
SPDT switch is used to enable or disable the circuit manually.

🛠️ Tools Used
KiCad 9.0 (Schematic + PCB Design)
ATtiny85 programming tools (optional)
Basic soldering & PCB fabrication tools

📂 Project Files Included
📌 KiCad 9.0 Project Structure:
Digital_Diya.kicad_pro → Main project file
Digital_Diya.kicad_sch → Schematic file
Digital_Diya.kicad_pcb → PCB layout file
Gerber/ → Fabrication output files (if exported)

🔌 Pin Connections (Example Reference)
ATtiny85 Pins (Typical Usage):
ATtiny85 Pin	Connected To
VCC	3.3V
GND	GND
PB0 / PB1	LED control output
PB2 / PB3	Microphone input
PB4 / ADC	LDR input
(Exact mapping may differ based on your schematic)

✅ How to Open in KiCad 9.0
Install KiCad 9.0
Open KiCad
Click File → Open Project
Select Digital_Diya.kicad_pro

View:
Schematic → Digital_Diya.kicad_sch
PCB → Digital_Diya.kicad_pcb

🏗️ How to Generate Gerber Files
Open PCB Editor
Go to File → Fabrication Outputs → Gerbers
Select layers
Click Generate
Export Drill files also

✅ Applications
Smart LED diya decoration
Sound activated night lamp
Festival DIY electronics project
IoT/Embedded basic demonstration

📌 Future Improvements
✅ Add PWM dimming for LED (flame effect)
✅ Add multiple LEDs for diya ring effect
✅ Add rechargeable Li-ion charging module
✅ Add automatic ON/OFF based on both sensors

👤 Author
Vivek Kumar Vishwakarma

3rd Year ECE | Embedded Systems | IoT | Robotics | AI/ML
VIT Bhopal University
