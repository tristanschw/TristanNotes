Before the introduction of cyclic loading, we should consider that most loadings in application are not static loadings. Even in the case of a bridge, building or the turbines in a RR Trent 1000, there is no such thing as a static loading. Cyclic loadings must be introduced.

When dealing with variable loadings, there is a new set of parameters which we will define: mean stress, stress amplitude, stress range, and stress ratio. Their accompanying strain subjects can also be described

![[Pasted image 20210504110330.png]]

Note: Sometimes there is a special case of zero mean stress.

** #meanstress ** (see image above for equations)
![[Pasted image 20210512142518.png]]

Increasing the #meanstress increases the chance of failure. For #meanstress less than zero, the life of the component increases since this indicates that the stress is compressive and closes any cracks [[Fracture Theory]] that may arise.

**Hysteresis Curves:**
As the number of loading cycles increases more plastic work is stored in the material and eventually leads to material failure. [[Damage in Materials]]
A hysteresis describes a loading path, and the area under the curve is the energy stored from plastic work in the material. 
![[Pasted image 20210504110735.png]]


**The equations for describing Cyclic Loadings are shown below**
![[Pasted image 20210504111427.png]] ![[Pasted image 20210504111443.png]] where ![[Pasted image 20210512151228.png]]


**When dealing with cyclic loading, we want to determine how many stess/strain cycles we can apply: $N_{f}$**

For high cycle #fatigue, which is any load > $10^{3}$ cycles, the **Basquin equation** is used (this equation applies only to $\sigma_{mean} = 0$

![[Pasted image 20210504111837.png]]

Or the **Modified Basquin equation**, when #meanstress is non-zero

![[Pasted image 20210504111948.png]]

**Endurance / Fatigue Stress**: A stress amplitude below which the material can be cyclically loaded for infinite life --> **it never fails.**
**Endurance / Fatigue Strength**: The maximum completely reversed cyclic stresses that a material can withstand for indefinite number of stress reversals.


Observation of two materials and their cyclic response.
(1) This material has a clear saturation point--> an endurance limit
(2) Continuous decrease, which means that the material never fails. To apply a theoretic endurance limit, we choose a stress amplitude value of $10^6$ cycles and plot that point on the stress-life ($N_f$) curve.
![[Pasted image 20210504112356.png]]

Taking the entire curve above on a log-log scale returns a strain line with slope of b and intercept of log(A) by the equation:
![[Pasted image 20210504112644.png]]
and 
![[Pasted image 20210504112706.png]]


For information on **Gerber, Goodman, and Soderberg Fatigue Criteria** see [[Fatigue]]

For cyclic loads applied on a three-dimensional body, the bending and moments will be fluctuating. Due to this fluctuation, the loads will have a mean and an amplitude.

For example, given a torsion (torque) on a body, there will be a $\T_{min}$ and $\T_{max}$ which means we must find a $\tau_{mean}$ and $\tau_{amplitude}$

First, we will need to find the amplitude of the torque by $\frac{T_{max} - T_{min}}{2}$ 

Then, we need to convert the Torque to a Shear stress by the equation
$\tau_{xy,amplitude}= \frac{T_a *r}{J}$
where J is the polar moment of inertia: For cylinders: ![Theory | C3.1 Torsion Formula | Solid Mechanics I](https://lh3.googleusercontent.com/proxy/d3nIQAYmHNlAR9nOHJui1JYjORuK5c-546sg39aQch54Lb7nTY15jOUFlAHBVAS4A0Dt7GqquFrcCvZZ0WzeLAU5ZTsaDw2giQHkA8RbsaDP-JH8nSJWWRYwR8PlQTivVMq3Ynb7gUmumpPbqrdzuZMLPqlQJ03ClrQ2ng)
(Note: If the applied force is a bending moment then use the following: $\sigma_{xy,amplitude}= \frac{M_a *r}{I}$ )
where I is the moment of inertia.
#effectivestressamplitude
![[Pasted image 20210512151424.png]]
where 
#effectivemeanstress
![[Pasted image 20210512151434.png]]








