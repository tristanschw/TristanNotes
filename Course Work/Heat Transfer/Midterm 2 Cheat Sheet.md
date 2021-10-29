Discussion 4-7
---
**Chapter 4**
4.2: *Separation of Variables*

A two-dimensional rectangular plate is  
subjected to prescribed boundary conditions.
	1. General Solution for Temperature Distribution at $T$ in 2D Convection using Separation of Variables![[Pasted image 20211025214214.png]]
	2. Heat Flow Lines always run perpendicular to isotherms

4.4: *Nodal Analysis*
Assumptions: 1. Steady-State conditions 2. Two-dimensional conduction 3. Constant Properties 4. Uniform internal heat generation (if present)
1. Start with Energy Conservation Requirement at each node: example: $q_1 +q_2 +q_3 +\dot{q}=0$
2. Evaluate each conductive node. example: $k \Delta y \frac{T_{m+1,n+1}-T_{m,n}}{\Delta x}$
3. Evaluate each convective node. example: $h (\frac{\Delta x}{2})(T_{\infty} - T_{m,n})$
4. Nodal Analysis Summary: ![[Pasted image 20211025214905.png]]
---
**Chapter 6**
Focus on convective heat transfer, non-dimensional numbers, setting up boundary layer  
equations, Reynolds Analogy, etc.  
*Question: When do I use local vs. average heat transfer? What is the difference?*
Local Heat Transfer is for finding regional temperatures. Average Heat Transfer coefficient is for the entire surface. The difference between the two is subtle. IF you need to find the average heat transfer coefficient of the 

6.1
6.2
---
***Important Numbers***
	**Prandtl Number**
		$Pr=\frac{c_p\mu}{k}$
		$Pr=\frac{\nu}{\alpha}$
	**Reynold's Number**
		External Flow, Flat Plate:
				$Re_L=\frac{U_{\infty}L}{\nu}$ 
				$Re_L=\frac{\rho U_{\infty}}{\mu}$
				
				**Sometimes Reynold's is used to find Velocity (thermophysical property)**
				
		Internal Flow, Cylinder:
				$Re_D = \frac{4\dot{m}}{\pi D \mu}$
		**Nusselt Number**
			General:
			$Nu_L=\frac{hL}{k_f}$
---
**Chapter 7**
• Understand where correlations are derived from (no derivations on exam).  
• Understand how to choose and appropriately use correlations depending on parameters given about the problem.
***General Methodology***
1. Identify the type of flow 
	a. What is the geometry?
	b. Calculate Reynolds number.
2. Identify the correct Nusselt correlation
3. Solve for heat transfer coefficient
4. Plug Equation One or Two
***Convection Equation for Evaluating Temperature*** 
	$$EQUATION-ONE: q_x''=h_xL(T_s - T_{\infty})...[\frac{Watts}{Meters}]$$
	$$EQUATION-TWO: q''=hA(T_s - T_{\infty})...[Watts]$$
	A flow is typically completely developed when $\frac{X}{D} > 10$
	
**Constant Temperature (Isothermal) Flow Over a Flat Plate**

$\def\arraystretch{10} \begin{array}{c:c:c} Laminar & Turbulent & Mixed \\ \hline \delta = 0.37(x)Re_x^{-1/5} & \delta = \frac{5(x)}{\sqrt{Re_x}} & -- \\ Nu_x = \frac{h_x*x}{k} = 0.332Re_x^{1/2}Pr^{1/3}& Nu_x = 0.0296Re^{4/5}Pr^{1/3}  & \bar{N_{UL}} = Pr^{1/3}*(0.037Re_L^{4/5}-0.037Re_{x,c}^{4/5}-0.664Re_{x,c}^{1/2}) \\ \bar{Nu_x} = \frac{h_x*x}{k} = 0.664Re_x^{1/2}Pr^{1/3}\end{array}$

**Constant Heat Flux Over a Flat Plate**

$\def\arraystretch{10} \begin{array}{c:c:c} Laminar & Turbulent & Mixed \\ \hline Nu_x = 0.453Re_x^{1/2}Pr^{1/3} & Nu_x = 0.038Re^{4/5}Pr^{1/3} \end{array}$

**Unheated Starting Length on a Flat Plate**

$\chi$=Unheated Starting Length
$Nu_{USL}\vert_{\chi=0} = CRe_x^{m}Pr^{1/3}$
$Nu_{x_{total}} = \frac{Nu_{USL}\vert_{\chi=0}}{(1-(\frac{\chi}{x})^{a})^{b}}$
![[Pasted image 20211027131922.png]]![[Pasted image 20211027132310.png]]

**Crossflow in Cylinders and shapes**

**General Nusselt Equation (for any shape in crossflow):**
$Nu_D = \frac{\bar{h}D}{k} = CRe_D^{m}Pr^{1/3}$ 

**General Reynolds**
$Re_D=\frac{\rho U_{\infty} D}{\mu}$ evaluated at $T_{film}=\frac{T_s + T_\infty}{2}$
![[Pasted image 20211027132702.png]]![[Pasted image 20211027222039.png]]

**Crossflow for Spheres**
$\bar{Nu_S} = 2 + 0.6 Re_D^{1/2}Pr^{1/3}$

*special case, Whitaker equation for spheres in cross-flow if the above equation does not satisfy*
![[Pasted image 20211028090810.png]]


**Drag Force**
$$C_d = \frac{F_D}{A_f(\rho V^2/2)}$$

*$A_f$*:Projected frontal area, perpendicular to the freestream
Sphere Frontal Area: $A_f = \pi D^2/4$

---
**Newton's Law of Cooling Derivations**
$\dot{q''_s} = h(\Delta T) = h(T_s-T_{\infty})$
$T_s =\frac{\dot{q''_s}}{h} + T_{\infty}$

**For Pipe Flow, to calculate the surface temperature of the pipe with a fluid running through it, use the same equation above to solve for $T_s$ (surface temperature) but use $T_{\infty}$ as the Mean Temperature of the Fluid running through it, $T_{m,o}$.**

Mean-Fluid-Temperature at any location in a pipe: $T_m(x)=T_{m,i} + \frac{\dot{q''_s} P x}{\dot{m}c_p}$

Recall, $\dot{m} = \rho V A_c$ where $A_c$ is cross-sectional area, and P is perimeter

---

**Chapter 8**
• Understand basics of velocity vs. thermal boundary layers and how to determine  
transition and fully developed lengths.  
• Understand calculation of mean velocity and temperature profiles.  
• Use the energy balance results (not performing derivation) to determine temperature at  
inlet/outlet of a tube.
Internal Flow, Cylinder:
				$Re_D = \frac{4\dot{m}}{\pi D \mu}$
				
**Entrance Region**

Approximate Nusselt Numbers at the Entrance Region: ![[Pasted image 20211028095444.png]]

**Entrance Length** If explicitly stated, flow is typically developed when x/D>10
$\def\arraystretch{10} \begin{array}{c:c} Laminar & Turbulent \\ \hline \frac{X_L}{L} = 0.05Re_DPr & 10<\frac{X_{L}}{D}<60 \end{array}$

**Entrance Nusselt**
![[Pasted image 20211028103435.png]] where ![[Pasted image 20211028103452.png]]


___

***Fully Developed Flow***

 **Constant Heat Flux**

- $\def\arraystretch{10} \begin{array}{c:c} Laminar & Turbulent \\ \hline 
\bar{N_{UD}} = 4.36 & (1) \bar{N_{UD}} = 0.023Re^{4/5}_D Pr^{n} \\ \end{array}$
- $T_m(x) = T_{m,i} + \frac{\dot{q''_s P x}}{\dot{m}c_p}$
- (1) Dittus-Boetler Equation, n = 0.3 for cooling, n = 0.4 for heating, applies to uniform heat flux and uniform surface temperature


**Constant Surface Temperature**
- $\def\arraystretch{10} \begin{array}{c:c} Laminar & Turbulent \\ \hline 
\bar{N_{UD}} = 3.66 & (1) \bar{N_{UD}} = 0.023Re^{4/5}_D Pr^{n} \\ \end{array}$

$T_s = \frac{T_s - T_{m,o}}{T_s - T_{m,i}} = e^{\frac{-PL \bar{h}}{\dot{m}C_p}}$

**Constant Outer Temperature (coolant at constant T)**
$T_{\infty} = \frac{T_{\infty} - T_{m,o}}{T_{\infty} - T_{m,i}} = e^{\frac{-\bar{U}A_s}{\dot{m}C_p}}$

where $\bar{U}$ is the *average heat transfer coefficient* which is further defined as
![[Pasted image 20211028104608.png]]
**Relate internal energy to external heat flux**
$\dot{m}=\rho V A$ , Internal Energy is then $q=\dot{m}c_p(T_o - T_i) [W]$ and Heat Flux is $\frac{q}{A_s} [\frac{W}{m^2}]$

**Chapter 8 +**
Simple Circuit involving insulation around a pipe
![[Pasted image 20211028104756.png]] ![[Pasted image 20211028104810.png]]


**Appendix**
**Lumped Capacitance:** 
- Biot Number: $Bi = \frac{\bar{h}L}{k}$
- Time to Cool/heat:![[Pasted image 20211027222753.png]]
![[Pasted image 20211027124216.png]]
![[Pasted image 20211027124314.png]]