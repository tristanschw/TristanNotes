#StrainBasedLoading is used for structural components that are expected to experience fluctuations in strain/displacement. #StrainBasedLoading is used for components that are likely to undergo localized plastic strain. 

**General Relation**
1. Small amounts of cyclic strain --> high cycle fatigue
2. High amounts of plastic strain --> low-cycle fatigue (see image2)
3. The distinguishing factor between whether a cycle is high or low cycle fatigue is based on the #transtionlife ($2N_t$ ) which equates the **elastic and plastic strain amplitudes**
$$\frac{\sigma_f^{'}}{E}(2Nf)^{b} = \epsilon_f^{'}(2Nf)^{c}$$
*Written to solve for $2N_t$:*
![[Pasted image 20210512145946.png]]

The equations for #StrainBasedLoading are as follows: 
(Arrives from the normalized #basquinequation)
$$ \epsilon_a = \epsilon_{a,e} + \epsilon_{a,p} $$

where 
$$ \epsilon_{a,e} = \frac{\sigma_f^{'}}{E}(2Nf)^{b}$$

$$ \epsilon_{a,p} = \epsilon_f^{'}(2Nf)^{c}$$

such that
**Eq 1: Total Strain Life for Zero Mean Stress** $$ \epsilon_a = \frac{\sigma_f^{'}}{E}(2Nf)^{b} + \epsilon_f^{'}(2Nf)^{c} $$

*Eq. 1 assume a mean stress of zero*
**Eq. 2: Total Strain Life for Non-Zero Mean Stress** $$ \epsilon_{a,modified} = \frac{\sigma_f^{'}}{E}(1-\frac{\sigma_m}{\sigma_f^{'}})(2Nf)^{b} + \epsilon_f^{'}(1-\frac{\sigma_m}{\sigma_f^{'}})(2Nf)^{c} $$

*Unlike mean stress, non-zero mean strain has no effect on fatigue life*
**Variable Definitions:**
![[Pasted image 20210512144420.png]]

**Method to Distinguish whether to use Total Strain, Plastic Strain, OR Elastic Strain Life Equations**
Look at the Size of the Hysteresis Curve**
Image2: ![[Pasted image 20210512144547.png]]

