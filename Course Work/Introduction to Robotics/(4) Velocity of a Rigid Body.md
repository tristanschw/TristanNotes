*The proper representation of rigid body velocity is through the use of #twists*
#spacial-coordinate-frame: fixed frame
#body-coordinate-frame: moving frame, in this case, rotating

*Typically, we want to describe all velocities of moving joints relative to another. In this sense, we want the velocity of the body coordinate frame in terms of the spatial coordinate frame*
How this is done:

**Representing #spacial-coordinate-frame and #body-coordinate-frame velocities**
Spatial Velocity:
1. Build the 3-D rotation matrix $$R_{t} = \begin{bmatrix}  cos(\theta t) & -sin(\theta t) & 0 \\ sin(\theta t) & cos(\theta t) & 0 \\ 0 & 0 & 1 \end{bmatrix}$$
2. Determine the spatial velocity by taking a derivative of the elements of the matrix and multiplying it by the transpose of the rotation matrix
![[Pasted image 20210916180132.png]]
3. Determine $\omega$ **I Don't understand this**

Body Velocity:
![[Pasted image 20210916182059.png]]





