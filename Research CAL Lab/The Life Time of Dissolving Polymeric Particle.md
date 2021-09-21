The problem of polymer dissolution may appear to be trivial, since there exists a comprehensive body of information on the theroy and practice of dissolution of patrticles of low molecular weight. However, as [shown] **there are fundamental differences in the process of dissolution of low-molecular weight and high molecular weight polymeric systems.**

Differences Between High and Low Molecular Weight Polymeric Systems:
1. Macromolecules (polymers) have a #reptation time
2. Polymer chains, being long and mutually entangled will be inhibited from entering the liquid phase due to the dynamic friction between the chains.

#reptation time: $t_{rep}$ Depends on the structures of the polymer and the molecular weight. 

- *Polymer Dissolution is a Step by Step Process (Explained First by Brochard and de Genne (1983)) [2] 
- Sharp boundary separating the glassy region (where solvent conc. is negligible) and the rubbery region (where solvent conc. it high). 
- Molecules in the rubbery region have high internal mobility
- Movement of polymer molecules in the solvent starts from the rubbery region
- ![[Pasted image 20210829100559.png]] 
[1]: Model demonstrating the mechanistic event of dissolution of solid polymeric particle.
	- **First**, the solvent diffuses into the glassy polymer inducing transition of the glass into a rubbery state. 
			#Reptation in the gel [3] :
			- Any glass(solid)-gel transition kinetics are neglected
			- The gel is held together by physical crosslinks provided by the entangled structure.
	- **Second**, Swelling of the network is followed by the dissolution of the polymer chains from the gel-liquid interface. 
			Behaviors at the Gel-Liquid Interface: 
			- Disengagement Process at the interface: The mobility of polymer chains at the gel-liquid interface of the swollen gel phase is high[1]. Because of this high mobility, this paper suggests that the time for molecular chains to disengage from eachother is a factor controlling the dissolution rate.
			- Mass Transfer Resistance: If the disengagement rate $k_d$ is relatively low, the resistance of the external boundary layer (governed by the mass transfer coefficient $k_i$) can be neglected. If surface disengagement and mass transport rates are comparable, then the process may be [diffusion limited] or #Disengagement-controlled  limited depending on the magnitude of the resistances at any instance. 
			- As the polymer chains #disengage, the boundary erodes and the polymer molecules move out from the gel-like phase to the less viscous liquid solution through a diffusion boundary layer.

#Disengagement is the rate at which polymer chains break from eachother.

[1]:*The mobility of the polymer chains at the interface of the swollen gel phase is high. These chains will tend to disengage from the interface and move to the solution phase by travelling through the diffusion boundary layer. For low-molecular-weight solids, the dissolution process has been envisaged as one that involves two steps: detachment of molecules from the solid surface followed by the diffusion of the species through an external mass transfer film into the bulk liquid*
[2]:*They proposed that when a droplet of semi-dilute polymer solution is placed in a solvent, the process of dissolution of the droplet comprises two steps. The first is the swelling of the polymer network by cooperative diffusion of the polymer chains and the second is the reptation of the polymer chains out of the swollen polymer network. These two steps are chiefly controlled by the cooperative diffusion coefficient, Scoop and the reptation time, rrse (De Gennes, 1971; De Gennes, 1979; Doi and Edwards, 1986). Brochard and De Gennes showed that an optimum droplet size of the order of dw~ may exist, below which the dissolution time will be equal.*
[3]:* #reptation suggests the movement of entangled polymer chains as being analogous to snakes slithering through one another.*

Alternative Papers: 
[a]: Lee and Fuller (1984): "The remaining portion of the chain extended away for the surface as dangling ends. Any shearing action arising out of the imposition of a hydrodynamic field is assumed to result in loosening and tearing away of individual macromolecules from their neighbours, who form the entangled mass"
[b]: Barham and Keller (1990):"postulated that on increasing the shear stress, these entanglements at the surface get torn away. The physical picture of disengagement at the gel-liquid interface proposed by [[The Life Time of Dissolving Polymeric Particle]] is somewhat similar to this."

**MATH**
1. Mass Conservation equation for diffusion of small solvent molecules in a stationary coordinate frame in terms of solvent volume fraction: 
	![[Pasted image 20210829111506.png]]
	*Important Assumptions: Diffusivity is assumed constant*
2. Local swelling rate is equal in magnitude but opposite in direction to the local flux of the solvent: ![[Pasted image 20210829111702.png]]
3. Rate at which the gel-solvent interface moves due to swelling: ![[Pasted image 20210829111903.png]](Left is due to dissolution, right is due to swelling of the network).
4. Equation 8 and 9 shouldn't be necessary, but if anything comes up about the reptation process/disengagement rate--just say that you don't know all the details, but the process is controlled by the resistance to mass transfer in the liquid.
5. The exact dissolution time $t_d$ can be determined from the following relation: ![[Pasted image 20210829112847.png]]
	a. It is noted that the equations (15-26) were solved using a [[Crank-Nicolson scheme]] and the dissolution time was determined as a function of initial particle dimension.
	
	**How Was This Model Tested?**
	1. Dissolution process was studied using two polymer-solvent systems of polystyrene in cyclohexane and poly(methyl methacrylate) in beneze at 35 and 30 degrees celsius (higher temperatures)
	2. Molecular weights of polymers determined by viscometric measurements
	3. Time readings for complete dissolution was noted by visual observation, which made reproducible readings within $\pm 5 seconds$

Figure 2: Dissolution time for different particle dimensions. As size increases, dissolution time increases. Disengagement rate and ($\mu_d$) and $\alpha$ #1b are held constant. ![[Pasted image 20210829114141.png]]

Figure 3: Dissolution Time vs Particle Dimension for different values of disengagment rate. As disengagment rate decreases, the dissolution time increases. 
- For low values of disengagment rate, the dissolution time varies linearly with particle dimension. 
- #Disengagement-controlled] dissolution can occur in the dissolution of very high-molecular-weight polymeric particles or when the dissolution occurs in an intense hydrodynamic field. ![[Pasted image 20210829115257.png]]

#1b: $\alpha$ is a parameter which depends on the hydrodynamics and kinematic viscosity of the solvent. $\alpha$ **depends on the external flow field** To account for various fluidic motions, we would have to change $\alpha$

Figure 4: Dissolution time with respect to changing values of $\alpha$
- As $\alpha$ decreases the dissolution time for a given particle size increases
- For high values of $\alpha$ the dissolution time varies linearly with particle dimension. For high values of $\alpha$ the process is #Disengagement-controlled 
 ![[Pasted image 20210829115937.png]]
 
 *Effect of a hydrodynamic field on the overall process of dissolution*
 - With increasing values of $\alpha$, the characteristic particle size of polymer increases. 
 - ![[Pasted image 20210829120448.png]]with stirring rate (in rpm) ![[Pasted image 20210829120615.png]]
	 - Note, we may be more interested in PMMA (poly-methy-methacrylate)
	 - The diffusivity of benzene in PMMA was estimated to be 4*10^-6 cm^2/s and PMMA in acetone was estimated to be 2.2*10^-7 cm^2/s (acetone solvent had lower diffusivity than benzene solvent)
	 - Additional graphs can be found on page 652 in pdf
	
	
	Final Remarks: 
	1. There is a critical size of a polymer particle, below which the time of dissolution of a solid polymer particle remains almost independent of the particle size
	2. This model defines a lower limit on the size to which a polymer particle should be reduced, since the dissolution time will remain independent of the particle size.
	3. To determine reptation time, all one needs to do is reduce the particle size continuously until a limiting constant dissolution time, which is independent of the particle size. This time will equal the reptation time.  