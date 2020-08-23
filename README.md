## Class overview

Exercises are basic implementations in Digital VLSI:
- Inverters
- Basic cells (NAND, OR, NOR, ...)
- Complex cells (AOI31, OA21 ...)
- ROM cells
- Capacitance and timing analysis

The technology used is SCMOS 0.25um (meaning 1 by 1 um grid size)

And most of ngspice scripts are LEVEL 3 spice simulations

For the schematic and extraction of the netlist, MAGIC was used (http://opencircuitdesign.com/magic/)

For the simulation of the netlist Ngspice, was used (http://ngspice.sourceforge.net/)

Every folder contains the exercise set and the necessary files for it to work and a report which 
explains further the steps and the findings of each exercise

### Exercise set 1
In exercise 1 we have to design an inverter in MAGIC with the following specifications:
- For both NMOS, PMOS -> Width of 3μm
- For both NMOS, PMOS -> Channel length 2μm

In exercise 2 we have to simulate the inverter in NGSPICE and confirm it works correctly.

### Exercise set 2
In exercise 1 we have to do the following:
- Plot Ids over Vds for different values of Vgs (For both NMOS and PMOS transistors)
- Calculate average and instantaneous resistance (both)
- Calculate RC equivelant resistance (both) using a 0.1pF capacitor in the output

In exercise 2 we do a transient analysis in PMOS and NMOS transistors and calculate the 
threshold voltage.
Also, we observe the voltage drop phenomenon in transistors (2 in series)

In exercise 3 we plot an inverter transfer function (Vout/Vin) for different values of Vdd 
and calculate the noise margins (together with a power analysis)

In exercise 4 we create a schematic of some complex gates and perform verification in Ngspice (
Base resistances for PMOS and NMOS are 31kΩ and 13kΩ)

Also, we perform a capacitance and timing analysis of such gate.

### Exercise set 3
In exercise 1 we have designed a full adder (1-bit) in MAGIC and then simulate in Ngspice:
- Design the schematic and line diagrams 
- Simulate the cell
- Connect the 1-bit adders and create an 8-bit adder

In exercise 2 we simulate a latch, it is made by a pass transistor and an SRAM cell at the output

In exercise 3 we simulate a positive edge flip-flop, it is made by a master and a slave latch in series

### Exercise set 4
In exercise 1 we have designed a 3 to 8 decoder:
- First design a 1-bit cell 1 to 2 decoder (AND gate) in MAGIC and then simulate it in Ngspice
- Design using the 1-bit cells and the necessary inverters a 3 to 8 decoder in MAGIC
- Simulate it in Ngspice

In exercise 2 we designed a 4-bit NOR ROM which stores 8 words:
- Design the 1-bit cells in MAGIC
- Design using the previous cells the ROM
- Simulate it using Ngpsice
