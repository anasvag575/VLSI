## Class overview

Exercises are basic implementations in Digital VLSI:
- Inverters
- Basic cells (NAND, OR, NOR, ...)
- Complex cells (AOI31, OA21 ...)
- ROM cells
- Capacitance and timing analysis

The technology used is SCMOS 0.25um (meaning 1 by 1 um grid size)
And most of ngspice scripts are LEVEL 3 spice simulations

### Exercise set 1
In exercise 1 we have to design an inverter in MAGIC with the following specifications:
- For both NMOS, PMOS -> Width of 3μm
- For both NMOS, PMOS -> Channel length 2μm

In exercise 2 we have to simulate the inverter in NGSPICE and confirm it works correctly.

### Exercise set 2
In exercise 1 we have to do the following:
1.Plot Ids over Vds for different values of Vgs (For both NMOS and PMOS transistors)
2.Calculate average and instantaneous resistance (both)
3.Calculate RC equivelant resistance (both) using a 0.1pF capacitor in the output

In exercise 2 we do a transient analysis in PMOS and NMOS transistors and calculate the 
threshold voltage.
Also, we observe the voltage drop phenomenon in transistors (2 in series)

In exercise 3 we plot an inverter transfer function (Vout/Vin) for different values of Vdd 
and calculate the noise margins (together with a power analysis)

In exercise 4 we create a schematic of some complex gates and perform verification in Ngspice
