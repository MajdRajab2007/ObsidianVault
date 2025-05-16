---
Tags:
  - LinearAlgebra
  - Matrices
---
 Now, it's going to be really useful if we can make a transformation matrix whose column vectors make up a new basis, all of its vectors are perpendicular or what's called Orthogonal to each other. In this note, we're going to look at this and why this is. But first, I want you to find a new operation on the matrix called the transpose. This is where we interchange all the elements of the rows and columns of the matrix, so I'll denote the transpose as :
 $$
 A^{T}_{ij}=A_{ji}
 $$
$$
 \m{1&2\\3&4}^T =  \m{1&3\\2&4}
$$

![[Pasted image 20250506173305.png]]

By defining a square matrix $A$ and having column vectors $a_1 a_2 a_3$ and so on, we can get $A^T$ by making those column vectors rows, if the vectors were orthogonal to each other and were all of unit length(i.e the vector dotted with itself is 1), and with the conditions written we find that $A^T \times A = I$ so $A^T$ is a valid **inverse** of A, and we call these vectors **orthonormal vectors** and we call the matrix A an orthogonal matrix.

*Note:* because an orthogonal matrix consists of vectors that are all of **Unit length** it scales space by a factor of 1, and its **determinant** must be +1 or - 1, where -1 flips space, sort of like a mirror.

___