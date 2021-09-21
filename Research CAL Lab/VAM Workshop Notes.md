The VAM workshop has a poster/short form presentation that might be better suited for the in space VAM. The presentations are meant to be longer like 20-30 min, so the short form will be less pressure. In the poster style, I think a larger fraction of time could be spent on the design. And the power/efficiency comparison could be relegated to be one element of the introduction/motivation for the work along with VAM's other benefits (assuming efficiency is better or equal to others) instead of the main focus of the presentation.

1.
Cannot write about printable volume, because they are all bigger
2.
Cannot write about material compatability
3.
Could write about part strength? 
4.
Could write about material usage?
5.
Could write about resolution
Acryonyms:
ECM: extracellular matrix
[[AM Abbreviations]]
**Overview of NASA Initiatives in AM** (2014)
:: https://ntrs.nasa.gov/api/citations/20150002612/downloads/20150002612.pdf

Mentions: IN Space
- gas turbine engine components from polymer and ceramic matrix composites
- fully non-metallic gas turbine engines and efficiency of such engines
Mentions: FOR Space
- AM rocket injectors
- copper combustion chambers and nozzle produced with SLM
- AM gimbal cone for the RL10 rocket engine
- AM hybrid turbomachinery disks
- Powder Bed Fusion, for rapid high-value propulsion

NASA's ultimate objective: Reduce money and time
Manufacturing components • Recycling • Creating sensors or entire satellites • Creating Structures Difficult To Manufacture On Earth Or Launch • Using resources on off-Earth surfaces
![[Pasted image 20210708091607.png]]

**BLANK**
![[Pasted image 20210708104704.png]] ![[Pasted image 20210708105019.png]]from: https://www.issnationallab.org/wp-content/uploads/09_Tracie-Prater_NASA.pdf

**NRC Report** (20--)
Objective: Manufacturing in Space, identify the science and technology gaps, assess the implications of space base AM
:: http://www.nap.edu/ download.php?record_id=18871

**A Portfolio of Fabrication and Recycling Technology Development for the International Space Station** (2018, AIAA)
:: https://ntrs.nasa.gov/api/citations/20180006405/downloads/20180006405.pdf
![[Pasted image 20210708092259.png]]
![[Pasted image 20210708092423.png]]
![[Pasted image 20210708092454.png]] (check status)
Mentions:
MCAM, flexible ceramics
**FABLAB**
::https://core.ac.uk/download/pdf/154738871.pdf
Logistics analyses indicate that a robust suite of in-space manufacturing capabilities will:  Enable manufacturing of large scale structures in space that are not constrained by launch requirements (i.e. volume), avoiding the complexities of modular launch and assembly in space  Decrease the mass of spares necessary for long endurance exploration missions  Use local resources and recycled materials for manufacturing, allowing dramatic reductions in initial mass requirements for buildup of infrastructure, particularly on planetary surfaces  Provide a capability to adapt to unanticipated circumstances, enhancing crew safety o Manufacturing of a permanent solution in response to a failure or a palliative solution that mitigates impact of failures until a permanent solution can be found o Manufacturing of tools or crew aids on site (includes biomedical applications and specialized science equipment) The FabLab is the key to demonstrating integration of a suite of manufacturing capabilities that will address the above needs in a single system.

**NASA Tech Flights Proposal** (2020)

![[Pasted image 20210708093528.png]]
Projects on the ISS: 
1. the Refabricator (Tethers Unlimited, USA) [7]
	a. FDM
	b. integrated printer/recycler which can melt a 3d printed part and re-extrude it into filament feedstock for further printing
	c. first demonstation of on-orbit recycling
2. the AMF (Made in Space) [4]
	a. FDM
	https://madeinspace.us/blog/2020/09/24/ceramics-manufacturing/
3. The BioFab Facilitiy (Techshot, nScrypt)
	a. Launched in July 2019, demonstrated 3D priting with several types of human cells in microgravity (https://ntrs.nasa.gov/api/citations/20190033333/downloads/20190033333.pdf) 
	a. extrusion-based hydrogel printing [8], [5]
	b. https://ntrs.nasa.gov/api/citations/20190033333/downloads/20190033333.pdf
	"Systems must fit into an EXPRESS rack limited to peak power consumption of 2000 watts, 576 lbm and 16ft^3 volume"
	c. Uses adult human cells (stem or plurpotent) and adult tissue derived protetins as its bioink to create viable tissue
	- printing cardiac like tissue, heart patches, evaluated on the ground under a microscope
	- Once printed, the structures will be placed in a tech-shot developed cell-culturing system that strengthens them over time to become self-supporting tissues that will remain solid once back in Earth's gravity (https://www.issnationallab.org/iss360/3d-printer-for-human-tissue-now-available-for-research-onboard-the-iss-national-laboratory/ [17])

	
5. **Organ-Aut (3D Bioprinting Solutions)** [6] 
	a. magnetic field gradients to guide magnetic nanoparticle-functionalized cell spheroids together 
	**https://www.researchgate.net/publication/343262551_Scaffold-free_Label-free_and_Nozzle-free_Magnetic_Levitational_Bioassembler_for_Rapid_Formative_Biofabrication_of_3D_Tissues_and_Organs**
	b. limited print size by the distance over which the magnetic field can manipulate and will require more electrical power to produce larger human organs
	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3773699/ (could be relevant work)
	https://www.3dprintingmedia.network/3d-bioprinting-solutions-presents-system-magnetic-3d-bioprinting-space/
6. CMM (Made in Space, not mentioned but is onboard as of May 2020)
7. Any other SLA systems?
	a. Allegedly: "Conventional layer-based stereolithography cannot be used in space because the liquid resin needs to form a flat interface with the ambient air. CAL, in contrast, enables resin printing because of its ability to print into enclosed volumes of liquid theoretically with zero relative motion between the printed object and the resin during illumination."

	**What We Said About CAL**
	CAL Advantages:
	1. print process is in a sealed container, which can be transported to the ISS, used, and returned to Earth with minimal human interaction
	2. Downtime for cleaning and maintenance is eliminated because there is no extrusion system--leads to more experiments than extrusion systems
	3. Absence of relative motion between the photo-crosslinked object (printed object) and the surrounding material, CAL works great for low-viscosity resins ([[GelMA]]) [9]
	4. Print times are much faster than layer-by-layer techniques [[Polyethylene glycol diacrylate (PEGDA)]]
	5. Enables in-situ 3D imaging, which is a challenge with other techniques that require removal of the printed part ([[Schlierren Imaging]])
	
	**Pick-Up Line**: *In summary, a CAL system combines 3D volumetric fabrication of a broad range of materials,
in situ tomographic imaging for process feedback and print analysis, and potential light-based
stimulation of cellular networks in a single platform with the benefit of a completely sealed print
volume. On board an orbiting spacecraft this translates to reduced space requirements, experience
needed to conduct AM experiments, and mission cycle time...Ultimately, CAL could be
used to fabricate parts of or entire organs that would be transported to Earth for human patients with damaged or debilitated organs, an application which fits well into NASA’s strategic objective of commercializing low Earth orbit activities to maintain constant human presence in space.*

Methodology: In the following flight test, we will use CAL to fabricate polymer components and hydrogel ECMs in microgravity, and identify any specific capabilities or limitations of CAL in space. 
Properties to be examined: 
**Accuracy**
**Material Properties**
**Parasitic Flow of Resin/Mass Transport**

[[VAM Workshop Resource Files (For Weekend Reading)]]
Chang, Bolan "Space Printing"
Characteristics of BFF Techshot (Based on 3Dn-300 BioAssembly tool, because paper mentioned it was this but flybilized)
Printable Volume: 300mm x 300mm  (Z-Axis: 150mm)
X-Y Max Speed: 300mm/s
Z Max Speed: 50 mm/s 
Print Resolution: X-Y: 100 nm Z:  100nm
Power Consumption: 120/240V AC, 20A
Weight: 227kg
**Approximate the time required to print an equal sized object (volumetrically)-->Take X-Y-Z integral distance traveled for a print divided by max speed**

Requires compressed dry filtered air ot nitrogen 80-120psi 
Requires cleaning print tips after each session for residual resin and disinfect fluid path
All materials were purchased presterilized before launch
Has multiple sizes and styles of syringes, gas permeable bags, sterilization pouches
Affixed with Micro-dispensing, 3D printing, laser processing, pick & place
![[Pasted image 20210720164904.png]] 

The AMF (Made in Space) *Uses something discussed as "SBM-Spec"*
Printable Volume: 140mm x 100mm (Z-Axis 100 mm)
X-Y Max Speed: 300mm/s
Z Max Speed: 50 mm/s 
Print Resolution: X-Y axis: .15mm nominal | Z-axis: 75 $\mu$m 
Power Consumption: 28V DC @12A | Uses 600W
Weight: 45kg (on Earth)
Additional Benefits: Real Time Video and Status Monitoring, Modularity, Future plans to print satellite components for on-demand sattelite deployment capabilities.
![[Pasted image 20210720165404.png]]
**Approximate the time required to print an equal sized object (volumetrically)-->Take X-Y-Z integral distance traveled for a print divided by max speed (make sure to include x-y speed and z speed)