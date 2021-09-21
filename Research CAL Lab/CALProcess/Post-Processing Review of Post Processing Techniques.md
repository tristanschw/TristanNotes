[[CAL Process]]
**Objective:**
Discuss various methods employed by AM companies and their sister post-processing companies. Analyze design and practices.

1. Carbon3D
	a. **Smart Part Washer** Works by spinning parts at high g-load inside a #solvent bath followed by an "air spin". This is repeated a few times to get a high quality clean. 
	b. **Vapor Degreasing** see: https://www.sciencedirect.com/topics/engineering/solvent-cleaning

2. FormLabs
	a. **Form Wash** Using 90% or higher isopropyl alcohol, the bath is filled. Parts are placed into the bath (mechanically raised in and out or placed in a wire basket). An impeller at the bottom of the Form Wash spins to agitate the #solvent for the duration of the wash cycle. Liquid resin remains in the #solvent after dissolution. 
	b. Measuring #resin-concentration of IPA: A #hydrometer is used to measure the #resin-concentration in the IPA, and Formlabs recommends replacing the #solvent when a #resin-concentration reaches 10-12%. Often parts can begin feeling tacky when the #resin-concentration reaches 5-10%. *Using a #hydrometer we could examine the change in specific weight of the solvent to determine exactly how much solvent we should be using per print volume.*
	c. Washing prints with TPM (Triproylene gylcol monomethyl ether) dissolves liquid resin and is an alternative to IPA for part washing. *We should know whether this is compatible with our prints* (https://support.formlabs.com/s/article/Measuring-IPAs-Resin-Concentration?language=en_US)
	d. For bio-compatibility, we should always wash with IPA concentration of 99% or higher to comply with biocompatibility regulations. (https://support.formlabs.com/s/article/Form-Wash-Time-Settings?language=en_US)
	e. Formlabs has an article devoted to solvent wash times here: (https://support.formlabs.com/s/article/Form-Wash-Time-Settings?language=en_US) *We may be able to use this to compare our resins to optimize post-processing*
	
3. Post-Process (https://www.postprocess.com/carbon-webinar/)
	a. **Submersed Vortex Cavitation (SVC)** Fully immersed parts and print trays allow chemistry to access complex geometries. A vortex is generated through a strategic pumping action to provide further agitation to remove resin. Cavitation produces ultrasonic formation of vapor bubbles to create high frequency waves to loosen viscous and persistent resins. It's software controlled and used in partnership with Carbon.![[Pasted image 20210715134313.png]] Uses #Demi910Solution
	*Note*: Ultrasonics aid "loosening" more viscous resins. Some resins are far more difficult to remove than other.
	b. Has specific fixtures for Carbon's L1 and M2 printers
	Compatible with: 
	RPU 70
	RPU 130
	EPX 82
	EPU 41
	IND405
	MPU 100
	UMA 90
	#Demi910Solution ![[Pasted image 20210715135500.png]]
	Mentions: Flushing out resin is a constant. Must optimize Weight % of Resin in Solution versus time to clean part. Dirty solvent leads to sticky surfaces. ![[Pasted image 20210715135805.png]] ![[Pasted image 20210715135907.png]]
	(https://www.postprocess.com/wp-content/uploads/2018/09/White-Paper-Enhanced-Support-Removal-for-Stereolithography-SLA-Additive-Manufactured-Parts-with-an-Innovative-Chemistry-Solution-5.2019.pdf)
	![[Pasted image 20210715154122.png]]
4. VPS (Flammable Solvents) (https://www.youtube.com/watch?v=4F67g_F_L14&t=222s)
(https://www.elmaultrasonic.com/how-can-i-use-flammable-solvents-in-an-ultrasonic-cleaner/)
This method works best when the parts to be cleaned are relatively small and cleaning is done on an occasional basis rather than as a full-time procedure. 
![[Pasted image 20210715153936.png]]

Carefully place the parts in a flask or beaker and add just enough solvent to ensure they are fully immersed.  Cover the container loosely to minimize the vapor that will result during the cleaning process. 

_Containers should never be tightly sealed as expansion due to heat created by ultrasonic cavitation could cause them to break._

In this instance you can use tap water with a surfactant in the ultrasonic cleaning tank.  Before proceeding remember to degas the solution by selecting the “degas” mode (if equipped) or by running the cleaner for 15 to 20 minutes without a load or until bubbles no longer rise to the surface.

Flasks can be fixed into position in a mesh basket using flask clamps, and beakers can be supported using a beaker cover instead of a basket.

In either case, the bottom 1-2 inches of the containers should be immersed in the water. The ultrasonic energy will penetrate the glass walls and cavitation action will occur in the IPA.  At the conclusion of the process carefully remove the parts which, when dry, will be residue free.

You can purchase [flammable solvent beaker kits](https://store.tovatech.com/ultrasonic-cleaning-using-flammable-solvents-beaker-kits/) that are ideal for this option.

1.  Ultrasonic cleaning with flammable solvents is widely used to remove mold support and other surface contaminants from **3-D printed parts**. 
2.  **Surgical Implants.** One of the most common applications is cleaning surgical implants**.** These are frequently cleaned using IPA. Reasons?  It evaporates quickly, is relatively non-toxic, and residue-free.
3.  Small **X-ray tube components** are cleaned in a volatile solvent to yield absolutely contamination-free results.  In an example using three steps the first step uses the solvent to remove oils that are deposited on the stainless/Kovar assembly.  Following this cycle, the tank is drained and filled with acetone for the second cycle.  After the acetone is drained the tank is refilled with the solvent for the third ultrasonic cleaning cycle to achieve the extreme cleanliness required.

Baskets and Accessories Boost Ultrasonic Cleaning Efficiency

Ultrasonic cleaning baskets can help with the following:

1.  To keep products being cleaned from contact with the bottom of the ultrasonic cleaner tank. Otherwise severe damage and eventual leaking will result due to vibrations.
2.  To ensure cavitation (cleaning) action is maximized by holding products at the optimum level above the tank bottom.  This is why different tank dimensions call for correct basket specifications.

If you’re planning to clean parts with a flammable solvent (i.e., any liquid with a flash point) in an ultrasonic cleaner, there are several possible approaches to consider. The options available from Tovatech are as follows:

-   Clean Small Parts with Solvent in a Beaker
-   Clean Larger Parts in Low Flash Point Solvent (e.g., IPA, acetone)
-   Clean Micro Parts with Volatile Flammable Solvent in Elmasolvex VA
-   Switch to a Non-flammable Cleaning Agent

**thing to consider: If we are to use a flammable solvent, IPA, then we need to address how difficult it will be to get approval to use this solvent in space (let alone, on Zero-G)** alternatives may be Post-Process or Formlabs recommended TPM

This method should be considered: https://vacuumprocessingsystems.com/vacuum-cycling-nucleation-agitation-benefits
