**Linear Elastic Fracture Mechanics** #LEFM can characterize the serverity of a crack in a component using the stress intensity factor, K.

**Fracture Toughness:** $K_Ic$ #fracturetoughness #K
*A measure of a material's ability to resist failure due to a crack* Values of #criticalfracturetoughness  vary widely based on material, temperature, loading rate, and THICKNESS


**Plane Strain Fracture Toughness:**
*A measure of a given material's ability to resist fracture in the precense of a crack*

**Trends in Fracture Toughness**
1. Internally flawed materials 
2. Brittle materials naturally contain small cracks (glass, natural stone, ceramics, some cast metals). Because they materials naturally have cracks, even though they have a high yield strength, the theoretical yield strength can never be reached due to small flaws and a low fracture toughness. _See A1 for more information about this_
	1. Ultimate Tensile Strength of a Material in Tension: ![[Pasted image 20210506115812.png]]
3. A material can resist a crack without brittle fracture as long as the instantaneous K is *below* the value of $K_c$ #fracturetoughness #Kc
4. Thicker members have lower #criticalfracturetoughness until a worst-case limit is reached #planestrainfracturetoughness


**Stress Intensity Factor: (units of $MPa \sqrt m$)**
![[Pasted image 20210506124406.png]]
*A measure of the severity of a crack situation as affected by crack size, stress, and geometry*
where $S_g$ is defined as ![[Pasted image 20210506125341.png]] b= width, t=thickness, P=Force, 

To define #StressIntensityFactor, the material is assumed to behave linear-elastically (no plastic deformation). Subsequently K ( #StressIntensityFactor ) is used in #LinearElasticFractureMechanics #LEFM 
S : Stress
a : crack length

**Defining F in the stess intensity factor equation**
![[Pasted image 20210506125744.png]]
a) if $a/b<=0.4$ F=1
b) if $0.6<=a/b<=0.13$ F=1.12

![[Pasted image 20210506124224.png]]
(A1): Brittle materials have considerably higher strengths under compression than under tension, since the cracks/flaws close under compression and subsequently have a reduced affect. 

**Transition Crack Length**
*A point which marks whether the material will lose strength due to brittle fracture or lose strength due to yielding*
**Important because:** If a crack is above the transition crack length, the #LinearElasticFractureMechanics method should be applied. If the crack length is below the transition crack length, then yielding dominated behavior is to be expected, and there will be no loss of strength due to the crack propogating. 
**Equation to Determine the Transition Crack Length:**
![[Pasted image 20210506122945.png]]
The #transitioncracklength varies from materials, defects, and temperature.

**How to Understand (Graphically) whether a material will fail due to a Crack**
![[Pasted image 20210506123311.png]]

#RandomPlaneFact1
The relative sensitivity to flaws associated with different at values for different materials helps to explain a number of sudden engineering failures that occurred in the 1950s and 1960s. New highstrength materials, such as steels and aluminum alloys developed for the aerospace industry, had sufficiently low fracture toughness that they were sensitive to rather small cracks. One example was the British-made Comet passenger airliner, two of which failed at high altitude in the 1950s, with considerable loss of life in the resulting crashes. Other examples are the late 1950s failures of rocket motor cases for the Polaris missile, and the F-111 aircraft crash in 1969. Such failures accelerated the development of fracture mechanics and led to its adoption by the U.S. Air Force as the basis of their damage tolerant design requirements. [[RandomPlaneFacts]]

A 90ft diameter and 50ft high tank in Boston was filled with 2 million gallons of molasses. The tank failed in 1919 emptying molasses on the city of Boston due to a #crackgrowth in ductile steel. 
