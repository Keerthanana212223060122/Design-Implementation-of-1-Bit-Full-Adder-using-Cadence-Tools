# Design-Implementation-of-1-Bit-Full-Adder-using-Cadence-Tools
Ex No: 05     Design & Implementation of 1 Bit Full Adder Using Cadence EDA Tools   

Aim:
To design and implement a 1-bit full adder circuit using Cadence EDA tools and to understand its behavior in digital arithmetic operations.

Tools Required:
•	Personal Computer
•	Cadence Virtuoso Software

S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.
•	File –New – Library
•	Name: Give name for ur library Ex: VLSILAB_EXP_1
•	Enable Attach to an existing technology library, Click OK
•	Attach the library to the technology library gpdk045.Click OK
ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)
•	File-New-Cell view
•	Setup the new file form
	Library: Select the one you created.
	Cell: Give the experiment name Ex: Inverter ViewSchematic
	Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
	Click on browse. This opens the library browser
	Now select the appropriate library for components like 
	Gpdk45 ------------------------nmos1v, pmos1v
	Create Input and Output pins
	Make the connections by using fixed narrow wire key
	Click Check and Save button

![WhatsApp Image 2024-11-15 at 17 40 37_a48f2290](https://github.com/user-attachments/assets/d7924ba3-6db7-442d-914d-b62c8c9cad08)


 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 
	Create – Cell view – From Cell view
	The cell view from cell view window appears
	Check Lib Name, Cell Name, From View name must be schematic Press ok
•	Now Symbol generation form appears. Click Ok If No changes required
•	A new window with with default symbol is created.
•	Edit the symbol if you want to give actual symbol shape else continue.
•	Execute Create-Cell view-from cell view
•	Library Name and Cell Name must be same which you have used for schematic. Press OK
•	Check for the position of pin side.Prss OK
•	Edit for the shape by Create-Shape-Choose required options to edit.

 ![WhatsApp Image 2024-11-15 at 17 40 35_3fbf8fe6](https://github.com/user-attachments/assets/f7502e08-5de2-4355-a335-2515dbdc35de)



iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view
	Setup the new file form
	Library: Select the one you created.
	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
	View: Schematic
	Type: Schematic press OK
•	Follow the step 3(ii) d to make the required connections


![WhatsApp Image 2024-11-15 at 17 40 36_af38408a](https://github.com/user-attachments/assets/46ebcab0-3b6b-4e01-9641-73e414ee7dab)

 
Analog simulation by SPECTRE.
•	In test cell view window
•	Launch – ADE L(Analog Design Environment)
	Execute Setup—Simulation/directory/Host A new window opens
	Set the simulation window to spectre and click ok
	Execute Analysis – Choose. A window opens.
	Select the type and set the specifications and press OK
	Execute Output s—to be plotted – Select on Schematic
	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
•	Execute Simulation -- Net list and Run
![WhatsApp Image 2024-11-15 at 17 40 37_e77ab727](https://github.com/user-attachments/assets/b3dbb4c3-4040-4d37-9c9c-930f72f02800)



For Transient Analysis Settings and Output
 
![WhatsApp Image 2024-11-15 at 17 40 36_b2411291](https://github.com/user-attachments/assets/33ca6d6f-daa5-4d33-9b7a-100a340cfabc)

![Screenshot 2024-11-15 211308](https://github.com/user-attachments/assets/0da8553d-3ea1-4aab-86f4-17c9abe4075f)


 

Results:
The design and implementation of the 1-bit full adder using Cadence EDA tools were successfully completed. The simulation results verified the correct operation of the full adder, with accurate sum and carry outputs for all input combinations.
