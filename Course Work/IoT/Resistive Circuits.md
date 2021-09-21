**Lecture 5**

#Voltage #Current #Resistance #Resistor-Coding #Series #Parallel 

Resistance in #Series : $R_{eq} = R_1 + R_2$
Resistance in #Parallel: $\frac{1}{R_{eq}} = \frac{1}{R_1} +\frac{1}{R_2}$ Reduces to $\frac{R_1*R_2}{R_1 + R_2}$

Combinations of #Parallel and #Series 

![[Pasted image 20210915164939.png]]

**Lecture 6**
Measuring Current, Voltage, and Resistance

![[Pasted image 20210915165842.png]]
1. Voltmeter 
	a. Must be placed in #parallel with circuit element
	b. Measures the difference in electrical potential between two points in an electric circuit
	c. HIGH input resistance so that it diverts a minimal amount of current away from the intended path.
	
	![[Pasted image 20210915165409.png]]
	#Symbol: ![[Pasted image 20210915165711.png]]
	
2. Ammeter
	a. Must be placed in #series with circuit element
	b. Measures the current 
	c. LOW input resistance because it measures the flow of electrons. A high input resistance would slow the flow.
	
	![[Pasted image 20210915170036.png]]
	#Symbol: ![[Pasted image 20210915165633.png]]

3. Ohmeter
	a. Placed in parallel across terminals
	b. Requires that you disconnect all sources to achieve unbiased measurements because the ohmmeter sends it's own current through each unknown resistance to measure the current out. The loss of current is equal to the resistance
	c. Requires a high input resistance
	
**Nodal Analysis for Resistive Circuits**
Two Methods:
1. Kirchoff's Voltage Law ( #KVL)
	- The sum of all voltage drops or rise in a circuit loop is zero
	$V_{AB} + V_{BC}+V_{CD}+V{DA} = 0$
2. Kirchoff's Current Law ( #KCL)
	- The net current flowing into or leaving any node is zero
	$\sum I_i = I_1 + I_2 +I_3 +I_4 =0$

Process for Nodal Analysis: 
1. Label all currents going into or out of a resistance 
2. Label all points in which there is a diversion of current streams (label nodes)
	a. If voltage at a node and resistance is known, the current before the resistor, $I_1$ is equal to: $I_1 = \frac{V_1 - V_a}{R_1}$ can be determined by the difference in voltages across the resistor divided by the resistance.
	b Otherwise, current can be found by applying Ohm's Law
3. Apply #KCL
4. Solve for unknown resistances, currents, voltages

Process for Mesh Current Analysis
1. Label all currents going into/out of resistances
2. Identify (indicate) the closed loops of the circuit
3. Starting at the Voltage Source, Determine the currents by relating the current downstream as the difference in the current upstream.
![[Pasted image 20210915180551.png]]
	a. $I_4 = I_1 - I_2$
4. Apply KVL about the closed loops by exploiting relationships of Ohm's Law
	a. In the above image, $V_1 - I_1*R_1 - I_4*R_4 = 0$
	
**Lecture 7**

Voltage and Current Dividers
1. A passive linear circuit that produces an output voltage that is a fraction of it's input voltage. 
2. Two resistors can be used as voltage dividers by placing a channel in between the two resists. The output voltage is then characterized whether there is a load attached to the output voltage or not. 
	*No Load*
	$$V_{out} = V_1 \frac{IR_2}{I(R_1+R_2)} = \frac{V_1R_2}{R_1 +R_2}$$
	*With Load*
	$$V_{out} = V_1 \frac{IR_2}{I(R_1+R_2)} = \frac{V_1(R_{2L})}{R_1 +R_2}$$
	where $$R_{2L} = \frac{R_2R_L}{R_2+R_L}$$
1. A common example of a voltage divider is a #Wheatstone-Bridge
	a. Used to precisely measure low resistances. Some working applications are measuring temperature, light and strain. 
![[Pasted image 20210915182421.png]]


**Lecture 8**
*Multiple Supply*

