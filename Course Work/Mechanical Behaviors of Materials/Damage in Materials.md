Damage in Cyclic Loadings:

By evaluating the stress-life equation in Mathematica
Delepsilon = 2*(of/E *((TwoNf)^b + epsilonf(TwoNf)^c));
TwoNf=1/epsilonf*(Delepsilon/2 - of/E - (TwoNf)^b)^(1/c);
![[Pasted image 20210504165505.png]]

We can determine the damage each type of loadreversal contributes to the block loading. Each "block" is simply an individual hysteresis curve, and the total damage done is $B_f=1/B_1$ where $B_1 = \sum(1/ 2N_f)$

To determine the percent damage done per block, one only needs to look at the damage per block $1/2N_f$ divided by the total damage $B_f$

Important note: high cycle #fatigue i.e >$3*10^7$ has a small damage accumulation, and the effect of high cycle #fatigue on the total damage can typically be neglected. 
