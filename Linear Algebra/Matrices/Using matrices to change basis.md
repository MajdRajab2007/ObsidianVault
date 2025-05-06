We can use matrices to change the basis of vectors 
![[Pasted image 20250501211643.png]]

given a vector system in a non traditional system (i.e not e1 and e2)
we can find the transformation to get a vector $v$ in that system to a traditional system by :

1. writing the basis vectors as a matrix like above
2. applying that matrix to the vector $v$
and if we wanted to do it the other way around we can get the basis for the traditional system in reference to the non traditional system by finding the inverse matrix and applying it to the vector

***Note**:* to get the inverse matrix you:
1. keep the diagonal elements the same
2. flip the (-) on the sub diagonal sides
3. divide by the determinant

This can also be done with projections like written before on the notebook ***if*** the vectors are orthogonal

![[Pasted image 20250506171753.png]]
but if we wanted to apply a transformation for a vector $\mycolv{x\\y}$ defined in bear's coordinate system, we need to take $\mycolv{x\\y}$ and make it in our system then apply the transformation the change it back to bear's system by **applying $B^{-1}$** (where $B$ is the matrix that turns $\mycolv{x\\y}$ into our system)
___