Stress Criteria such as #VonMises and #Tresca are useful because they reduce the 9 terms of a stress tensor into one component that can be easily compared to a yield stress value for asserting the factor of safety.

Stress Failure Criteria can be #VonMises or #Tresca or #MaxShearStress or #MaxNormalStress 

![[Pasted image 20210512125836.png]] ![[Pasted image 20210512125853.png]]

Brittle Materials: Max Normal Stress
Ductile Materials: Tresca and Von Mises
**General Method to find #VonMises , #Tresca , #MaxShearStress and #MaxNormalStress **

1. Determine principle stresses:
![[Pasted image 20210512123707.png]]

** #VonMises ** (characterized by #OctahedralStress)
$$\sigma_{eff} =\frac{1}{\sqrt{2}}\sqrt{(\sigma_1 - \sigma_2)^{2} + (\sigma_2 - \sigma_3)^{2}+(\sigma_3 - \sigma_1)^{2}} $$
or, if there is a shear stress present:
$$\sigma_{eff} =\frac{1}{\sqrt{2}}\sqrt{(\sigma_1 - \sigma_2)^{2} + (\sigma_2 - \sigma_3)^{2}+(\sigma_3 - \sigma_1)^{2} + 6(\tau_{xy}^{2}+\tau_{yz}^{2}+\tau_{xz}^{2})} $$

where 
* #safetyfactor for VonMises = $x_{vm} = \frac{\sigma_y}{\sigma_{max}}$ *
* *#OctahedralStress (Otherwise known as Von-Mises Stress Criteria) Described as a plane that is equally oriented with all three axes*

![Octahedral stresses | pantelisliolios.com](https://pantelisliolios.com/media/octahedral-stresses.svg)

* Equations for Octahedral Stress
![[Pasted image 20210512120401.png]]


** #Tresca **
![[Pasted image 20210512124532.png]] ![[Pasted image 20210512125940.png]]
**Once the value of $\tau_{max}$ is determined from the Tresca Criteria, we can compare $\tau_{max}$ with the yielding shear stress, $\tau_{y}$**

* where $\tau_{y} = \frac{\sigma_y}{2}$

* and #safetyfactor for #Tresca is $x = \frac{\tau_y}{\tau_{max}} = \frac{\sigma_y}{\sigma_{max}}$

* and #MaxStress = ![[Pasted image 20210512125320.png]]



** #MaxShearStress **
![[Pasted image 20210512124615.png]]



** #MaxNormalStress **
![[Pasted image 20210512124636.png]]
