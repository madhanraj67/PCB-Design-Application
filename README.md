# PCB-Design-Application
# Aim
To prepare the pcb-design application for the given circuit.

# Software required
Eagle

# Procedure

1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory


A rain sensor alarm typically works by detecting the presence of raindrops and triggering an alarm or alert system. The theory behind its operation involves using a sensor to detect changes in conductivity, capacitance, or resistance caused by the presence of water.

One common type of rain sensor uses a simple circuit with two conductive electrodes. When raindrops fall on the electrodes, they create a conductive path between them, changing the resistance or capacitance of the circuit. This change is detected by the sensor, which then activates the alarm or alert system.

Another type of rain sensor uses an optical method, where an infrared LED emits light that is reflected back to a receiver. When raindrops are present, they scatter the light, reducing the intensity of the light received by the receiver. This change in light intensity is detected by the sensor, triggering the alarm.


### Working 

Components:

Raindrop sensor module
Buzzer
10kΩ resistor
5V power supply
The raindrop sensor module has a series of traces on its surface that change resistance when wet.
When it starts to rain, the module becomes conductive, allowing current to flow from the +5V through the module to ground (GND).
The 10kΩ resistor is used to limit the current to a safe value.
When current flows through the module, it triggers the buzzer, producing an alarm sound.

# Circuit Diagram
![WhatsApp Image 2024-05-13 at 18 51 31_e3bb5a24](https://github.com/Iyalarasu1/PCB-Design-Application/assets/144870581/f85c6948-f31c-4a35-8138-fbe9b10345ab)


# Output

### Schematic diagram
![WhatsApp Image 2024-05-13 at 18 39 55_851619cb](https://github.com/Iyalarasu1/PCB-Design-Application/assets/144870581/03a2942c-9e3c-42f7-9709-76242ff52d58)


### Layout diagram
![WhatsApp Image 2024-05-13 at 18 39 55_e78c464a](https://github.com/Iyalarasu1/PCB-Design-Application/assets/144870581/26dad029-fedf-4cfb-a4ae-ade03605230d)


# Result

Therefore PCB Design was successfully Completed
