---
aliases: []
---

- **Eigenvectors** are introduced as a concept that can be combined with the idea of changing basis, which was discussed earlier in the course.
- The lecture emphasizes the importance of **diagonalization**, a powerful tool for performing efficient matrix operations.
- An example is provided where a transformation matrix ( T ) represents the change in location of a particle after a time step. The initial position is described by vector ( v_0 ), and the new position after one time step is ( v_1 = T v_0 ).
- To find the position after multiple time steps, the lecture explains that ( v_n = T^n v_0 ), highlighting the computational challenge of multiplying the matrix ( T ) many times.
- By using Diagonal Matrices like $\m{2&0\\0&2}$ where the diagonals are non zero, we can multiply it by itself n number of times and get the result as $M^n =\m{2^n &0\\0&2^n}$
![[Pasted image 20250511173432.png]]
Where the matrix $C$ contains our **eigen vectors** and $D$ contains our **eigen values** and *T* is the matrix we want to multiply

#### Example: 
![[Pasted image 20250511180157.png]]