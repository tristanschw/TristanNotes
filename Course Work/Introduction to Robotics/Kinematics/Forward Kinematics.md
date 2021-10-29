**Forward Kinematics** is the problem of finding where the end effector of the robot ends up when we pick particular values of $\theta$. We can use the **Product of Exponentials** formula to write down an expression for the forward kinematics map.

*Robots have links (arms) connected by joints (elbows and the like*
![[Pasted image 20210918165209.png]]
**Joints** (Blue Cylinders)

#Revolute & #Prismatic

#Revolute joints: pure rotation
a. Twist, $\xi = \begin{bmatrix}  v \\ \omega \end{bmatrix}$ = $\begin{bmatrix} -\omega \times q \\ \omega \end{bmatrix}$
b. Cross-product equation: ![[Pasted image 20210928202826.png]]
#Prismatic joints: pure translation
a. Twist,  $\xi = \begin{bmatrix}  v \\ 0 \end{bmatrix}$ where $v$ is a unit vector pointing in the direction of translation. 

#Joint-Space: The set of all possible orientations of the joints. Consider this the total range of motion. 

*Calculating the final position of the end effector:*
1. Calculate the #Twist for each joint (Recall #Revolute or #Prismatic)
2. Use the **Product of Exponentials**,i.e. $$g_{st} = e^{\hat{\xi_{1}}\theta_1}e^{\hat{\xi_{2}}\theta_2}...e^{\hat{\xi_{3}}\theta_3} \times g_{st}(0)$$
	*where $g_{st}$ is the reference configuration (when all joint angles are at zero).*
	
	

	