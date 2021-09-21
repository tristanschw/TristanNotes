Recall: $\omega$ = the direction of rotation, whereas $\hat{\omega}$ is the #skew-symetric-matrix of omega.

$\hat{\omega}b$ is actually equal to matrix $a \times b$

****Rigid Motion****
a) preserves distance between points *and* the angle between vectors
b) described relative to an inertial (non-moving) frame
c) consist of rotation and translation

3.0: #Affine Transformations
Given $q_a$ and $q_b$ in $R^3$ where $_a$ and $_b$ are reference frames, we can find $q_a$ by using equation #eq2dot22, ![[Pasted image 20210915092024.png]] 

*Note*: We write $g_{ab} = (p_{ab}, R_{ab})$ to shorten notation, but it means the same thing as #eq2dot22 

3.1 #Homogeneous Representation
	- Used to represent the transformation of points and vectors by rigid transformations in terms of matrices in R4
	- Representing **Points** in #Homogeneous Coordinates: 
		q= $\begin{bmatrix}  0 \\ 0 \\ 0\\ 1 \end{bmatrix}$
	2. Representing **Vectors** in #Homogeneous Coordinates: 
		v=$\begin{bmatrix}  v_1 \\ v_2 \\ v_3\\ 0 \end{bmatrix}$
		
*Note the difference in the last row, points have a 1 at the end, vectors have a 0. This is because of matrix addition/subtraction:** ![[Pasted image 20210916182537.png]]
3. If we want to find the coordinates of point $q_a$ after a rotation and translation, we use the 4 x 4 matrix $g_{ab}$ =$\begin{bmatrix}  R & p \\ 0 & 1\end{bmatrix}$
Note: *Sometimes the 1 in the bottom right hand corner of the above matrix is replaced with a scalar constant to represent dialtion (>1) or contraction (<1)*
		
#composition-rule for rigid body transformations: To get to any matrix, we can multiply the previous matrices together to get the new matrix relative to the previous ones.
**Rotating a Rigid Body**
$\frac{dp}{dt} = \dot{p}(t) = \omega \times p(t) = \hat{\omega}p(t)$
if you solve the equation above, you get $p(t) = e^{\hat{\omega}p(t)}$

where $\hat{\omega}$ is the #skew-symetric-matrix of $\omega$
	**3.2 Exponential Coordinates for Rigid Motion and Twists**
	Important Because: If we want to desribe the rotation of a link of a robot about a fixed axis, we only need to write the rotation matrix (R) as a function of $\omega$ and $\theta$
	
**Converting Exponential Coordinates to Homogeneous Coordinates**
![[Pasted image 20210915094153.png]]
	*Simple situation. Robotic arm rotating about axis $\omega$ with origin at q. There is a point on the tip of the arm, p, which is moving at a velocity p(t)*
![[Pasted image 20210915094240.png]] #eq2dot25
	
#eq2dot25 can be written into homogeneous coordinates by making ![[Pasted image 20210915094456.png]]

where v in the above equation is $- \omega$ x q

**Twist: Coordinates for Rotation About a Line**
#Twists are matrices, defined in R^6. It is a 1x6 (column) vector. The first three elements are the linear velocities, $\nu$. The last three elements are the $\omega$ (angular) velocities. 

Define $\nu = \omega \times q +h\omega$
where $\omega$ is the axis of rotation, $q$ is a point on the axis, and $h$ is the pitch

![[Pasted image 20210915094755.png]]! The above image has a transformation of: [[Pasted image 20210915094805.png]]

However, to compute this in relative exponential #Twist coordinates, we need to generate a different methodology: 
![[Pasted image 20210915095522.png]]![[Pasted image 20210915095533.png]]

**Screws: a geometric description of twists**
*Screw motion is described as rotation about an axis along with a translation about that same axis (like a screw)* This motion is *equivalent* to applying a linear velocity (v) and angular velocity ($\omega$) over $\theta$ units of time.
	v = v(perp) + v(parallel)
	mathematically, v(parallel) = h$\omega$
	and v(perp)= $-\omega \times q$
- Screw motion has three components: 
	- axis, l
		a. the most convenient way to define a screw motion is by:
			1. choosing q$\mathcal{E} \mathbb{R}$ such that it is on the screw axis
			2. define the axis of rotation, $\omega$
			3. Choose your angle of rotation about $\omega$ and with #pitch
	- pitch, h
		a. #pitch, **h**: ratio of translation to rotation $h=\frac{d}{\theta}$
		b. If h=$\inf$ then there is **no** rotation
		c. if h = 0, there is **no** translation
	- magnitude, M
		a. magnitude is only of rotation .i.e. $||\theta||$
- Screw motion represents rotation by an amount $\theta$=M about axis l, followed by a translation by an amount h$\theta$ parallel to axis l. 
- #Homogeneous coordinates of Screw motion: ![[Pasted image 20210915100216.png]]

**Screws and Twists: Why they Matter**
