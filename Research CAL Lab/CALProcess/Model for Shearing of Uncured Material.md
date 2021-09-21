[[CAL Process]]
Objective: Derive an equation for a non-newtonian fluid flow velocity, pressure force, shear stress, gradient friction force, viscosity, which can be verified using CFD.
CFD Software Idea : https://www.flow3d.com/products/flow3d-am/
https://science.sciencemag.org/content/sci/suppl/2019/01/30/science.aau7114.DC1/aau7114_Kelly_SM.pdf

Questions:
1.) What does it mean to be a semi-cured residual resin? 
- Its a pre-polymer (a monomer that have been reacted to an intermediate molecular mass state, with low cross-linking)
- It's a semi-solid non-newtonian fluid
- It is very sticky-->What is causing this stickiness?--> some level of polar bonding between surfaces
- If work is applied to the surface this will cause polymer chains to break up->lower viscosity
- MUST STUDY CHEMICAL EQUATIONS AND SUCH OF PHOTOPOLYMER RESINS 

Important Research Notes:
1.) Rheology is the study of the flow of matter primarily in the liquid state
2.) A liquid is said to *wet* a solid surface when there is an attraction (adhesion) between the wall and the molecules of the liquid which is strong enough to overcome the mutual attraction (cohesion).
3.) Visualization of Resin Viscosity (From Science paper) compares BPAGDA/PEGDA resin mixture, one with a 3:1 BPAGDA/PEGDA ratio and the other a 7:1 BPAGDA/PEGDA ratio. 
PEGDA (poly(ethylene glycol diacrylate)) ![[Pasted image 20210720125449.png]]
BPAGDA ((Bisphenol A glycerolate (1 glycerol/phenol) diacrylate) ![[Pasted image 20210718202459.png]]
It is clear that the 7:1 ratio flows much slower, indicating that BPAGDA (Bisphenol A glycerolate (1 glycerol/phenol) diacrylate concentration increases resin viscosity (amount of BPAGDA has a directly proportional to resin viscosity)

4.) What is BPAGDA and why does it make things stickier? (Probably because the molecule is much larger and hence higher concentrations make it more viscous)
C27H32O8
( #a1) Polar bonds (O-H) tend to wet polar surfaces but not wet non-polar ones (like wax)
Non-polar bonds (oil) tend to non-polar surfaces but not polar ones.
https://www.sciencedirect.com/topics/engineering/adhesive-resin

**From: Introduction to Plastics and Polymers**
:https://www.sciencedirect.com/topics/engineering/polar-polymer
"The polarity of a molecule affects the attraction between molecular chains. For example, if a molecule is more negatively charged on one end than the other, then this creates a *dipole*, which means that the bond is *polar*...Thus, polarity affects the structure of the polymer (due to the attraction of polar molecules) which inturn affects solubility and permeability of the polymer."
"Because hydrocarbon molecules are not significantly polar, hydrocarbons are non-polar along with hydrocarbon polymers. Generally, if a polymer is polar, it is more permeable to water than non-polar polymers.*This makes sense because of ( #a1)*

5.) Why can we not just use water to clear the residual prepolymer?
The polymer we are dealing with is non-polar, which means that it is more permeable to non-polar molecules. IPA, water, acetone, are considered polar solvents, but IPA and Acetone are great at dissolving non-polar substances because they have polar and non-polar ends. 

6.) How big are the particles of resin? Knowing that smaller particles have a larger relative adhesion force.

7.) The basic premise is that we want to study "Shear Stress Cleaning"


Action Plan:
1. Develop a hypothetical model to relate the situation described above (soonish)
2. Figure out how to model this in CFD (soonish as well)
*The thing we are looking for is: Force required to clear residual prepolymer*


