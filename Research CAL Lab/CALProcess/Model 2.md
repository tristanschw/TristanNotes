[[CAL Process]] [[Model 2]]

Prelim. Thoughts: 
1. Moore's Circle, How can we use the components of greatest shear force to understand the circumstance at hand
2. Who can we talk to? 
	1. Alexis Kominsky
	2. Phillip Marcus
3. What Papers can we read to get ideas: 
	1. https://royalsocietypublishing.org/doi/full/10.1098/rsif.2017.0298
	2. https://wyss.harvard.edu/technology/slips-slippery-liquid-infused-porous-surfaces/
	3. Keywords: {Polymer, Dissolution, Polar, Solvent}: http://wwwcourses.sens.buffalo.edu/ce435/Koenig03.pdf

Article 1: Royal Society Publishing

Article 2: SLIPS 

Article 3: Polymer Dissolution 
1. Chemical Structure and polarity determine dissolution of polymers.
	a. Always follow rule of "Like Dissolves Like"--If the chemical structure of polymer and solvent molecule differ greatly in polarity, then swelling and dissolution does NOT happen
		1a. Non-polar polymers mix infinitely with alkanes but do not mix with polar liquids as water and alcohols. 
		2a. Polar polymers do not mix with alkanes and readily swell in water.
		How does polarity affect solubility? ==Like dissolves like. Polarity of polymer and polarity of solvent must be considered==
		Why is "shear force departiculation important?"==Molecular mass of polymer affect solubility, as molecular mass of polymer increases, the energy of interaction between chains also increases==
2. Polymer Dissolution Models
	a. Schematic representation of one-dimension solvent diffusion and polymer dissolution process. ![[Pasted image 20210823222415.png]]
	b. The understanding of polymer dissolution begins with the interface above. After a certain time, t, the concentration of solvent in the polymer exceeds a critical value resulting in chain disentanglement and start of the dissolution. 
	c. **Five Types of Dissolution Models**
		1c. Phenomenological models with [[Fickian Equations]]
			- Attempt to physically describe the dissolution process and moving boundaries (4.1.1.) 
				Pros: 
				- First models for polymer dissolution, easily quantifiable, does not mention reptation.
				Cons: (Strong Opposition)
				- Many assumptions. Assumes that solvent flux into the polymer is  sufficient to carry away all the chains. 
				- Assumes the dissolution is disassociation-controlled though when the solvent concentration at the gel-liquid boundary reaches a constant concentration, the flux is no longer sufficient to carry all the dissolved chains.
				- Assumes that the glass-gel transition is rapid, and neglects any kinetics at the glass-gel boundary.
		2c. Models with external mass transfer as the controlling resistance to dissolution (4.1.2. ==Disengagment Dynamics==
			Pros: 
			- Predicts a lifetime of a dissolving polymeric particle in a ==hydrodynamic field.==
			- Incorporates reptation of polymer chains, disengagement of theses chains at the gel-liquid interface, diffusion in the boundary layer surrounding the gel-liquid interface
			- Includes experimental data (lot of graphs)
			- Incorporates a uniform stream of solvent moving with velocity
			- ==Discusses important relationships betweeen the diffusivity of the polymer, the external velocity, and the disengagement rate on dissolution time.==
			- Proved correct
			Cons:
			- None by author
		2ca. Models of Dissolution by mixed solvents (4.1.3) 
		3c. Stress relaxation models and molecular theories.
		4c. Analysis using transport models for swelling and scaling laws for chain disentanglement.*
		5. Continuum framework models. 

3. Discussion of Five Types of Dissolution Models
4. ==Each model contains elements of the "swelling", which is a state when the polymer is saturated with solvent, reptation, ==
	a. The multi-phase Stefan problem (4.1.1.) (https://www.jstor.org/stable/43645939) 
		Assumes Fickian solvent diffusion (*eh*) with two distinct boundaries. Assumed constant chain disassociation concentration, which is established immediately upon wetting the polymer surface. 
4. Analysis of the multi-phase Stefan problem (https://www.jstor.org/stable/43645939)
	4a. Dissolution is governed in two different ways:
	Dissociation Controlled: if the polymer diffusion rate in a liquid layer adjacent to the polymer-gel interface is faster than the disassociation rate.
	Diffusional-controlled: if the diffusion rate is slower than the disassociation rate. 
	*Note: Disassociation here refers to polymer chains breaking apart*
	![[Pasted image 20210823231943.png]] ![[Pasted image 20210823231958.png]]
	
5. Summary of (http://wwwcourses.sens.buffalo.edu/ce435/Koenig03.pdf)
	There are many different dissolution models and none are perfectly accurate. All make assumptions such as Fickian Dissolution, reptation modeling, diffusion coeficient, and assume a schematic similar to (![[Pasted image 20210823233416.png]]). The difference in models is largely dependent upon the kinetics assumptions which were made. For example, is the polymer chain disassociating completely controlled by the process at the gel-liquid interface (4.1.3)? Or does it "soak" into the gel-polymer interface and cause swelling(4.1.1)? Is the disassocation diffusional controlled or dissociation conrolled? Is the process Fickian? Do we use the model of reptation (4.1.2)? Do we assume that the resistance offered by the layer directly adjacent to the polymer is important to polymer dissolution (4.2.1)? Or, lastly, is the easiest method to model this system to use the stress relaxation with molecular theory proposed in (4.3.1) which relates the solvent flux in the system to the polymer concentration, the stress present in the system and the osmotic pressure?
	
	**==We NOW KNOW what dissolution models exist, now just choose one!**==
	08/23/21 Update: Selected Proper Dissolution Model for the Situation we Have. Next step is to review the math and understand the principles at hand. The model we will use is **4.1.2 Disengagement Dynamics**
	
	**DISENGAGEMENT DYNAMICS** : https://www.sciencedirect.com/science/article/pii/0009250994850100 [[Disengagement Dynamics, Polymer.pdf]]
	
	