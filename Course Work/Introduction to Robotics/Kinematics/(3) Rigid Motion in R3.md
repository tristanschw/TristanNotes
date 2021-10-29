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