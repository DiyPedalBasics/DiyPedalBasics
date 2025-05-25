---
title: "Introduction to Circuit Analysis 01: Voltage, Current, Resistance and Ohm's Law
layout: default
permalink: intro_01.md
---
# Introduction to Circuit Analysis 01: Voltage, Current, Resistance and Ohm's Law


## 1: Theory

Imagine a stream connecting two pools of water. The width of the stream limits how much water can flow from one pool to another. The water pressure each pool also affects the flow: Water moves from the point of the higher pressure to the point of the lower pressure. 

Electricity behaves in a similar way. There are three fundamental properties to understand: Voltage, Current and Resistance. 

- **Voltage** is the difference in electric potential between two points, like the difference in water pressure between the two pools. 
- **Current** is the amount of electric charge flowing, similar to the amount of water flowing through the stream
- **Resistance** limits the flow of current, like the width of the stream limits water flow.

They are linked through Ohm's Law, which states 

$$V = R\cdot I$$

Where: 

- $V$ is Voltage (unit in Volts, $V$) 
- $I$ is Current (unit in Ampere, $A$) and
- $R$ is Resistance (unit in Ohms, $\Omega$). 

If a certain current flows through an object with a known resistance, you can calculate the voltage drop across this object. Conversely, if you know the voltage drop across an object and its resistance, you can calculate the current flowing through the object by rearranging the formula for $I$: 

$$I = \frac{V}{R}$$

Unlike current and resistance, **voltage is a relative property**, not an absolute one. When we say "there is a voltage at this point", we mean there is a difference in electric potential between that point and another point we define as "ground". The ground is considered to have a potential of $0V$.

In future lessons, we will say "nodes" instead of "points". 

## 2: Circuit Symbols

| Symbol | Description |
|--------|-------------|
|![Voltage Source](/assets/schematics/symbols/voltage_source_v01.svg)| Represents a voltage source; Across the two nodes this symbol connects there is always a specific voltage drop.|
|![Battery](/assets/schematics/symbols/battery_v01.svg)| Represents a Battery, a voltage source.|
|![Current Source](/assets/schematics/symbols/current_source_v01.svg)| Represents a current source; There is always a set current flowing through this line.|
|![Ground](/assets/schematics/symbols/ground_traditional_v01.svg) ![Alt Ground](/assets/schematics/symbols/ground_alt_v01.svg) | This is the ground symbol, which marks the node it's connected to as ground.|
|![Resistor](/assets/schematics/symbols/resistor_new_v01.svg) ![Alt Resistor](/assets/schematics/symbols/resistor_old_v01.svg)| This is a resistor. It has a constant Resistance $R$.|

## 3: Calculation Example

//TODO

## 4: Exercises

//TODO