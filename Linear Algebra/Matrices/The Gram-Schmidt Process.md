---
tags:
---
## Understanding Orthonormal Basis

The video lecture focuses on constructing an **orthonormal basis** from a set of **linearly independent vectors**.

### Steps in the Gram-Schmidt Process

1. **Start with the first vector**: Normalize it to create the first basis vector $e_1$ .
2. For each subsequent vector, project it onto the existing basis vectors to find components that are orthogonal.

### Finalizing the Orthonormal Basis

- Continue the process for all vectors, ensuring each new vector is orthogonal to the previous ones.
- The result is a set of orthonormal vectors that simplifies transformations and calculations in linear algebra.

![[Pasted image 20250507165215.png]]
in our example, this is how we found the first two basis vectors $\hat{e_1}$ and $\hat e_2$.

then seeing as $v_3$ is not in the same plane as $v_1$ and $v_2$ we need to write it as a linear combination of the two basis vectors 
$$
u_3 = v_3 -(v_3\cdot e_1)\cdot e_1 -(v_3\cdot e_2)e_2
$$
then we need to normalize $u_3$ so that it becomes a valid basis vector by taking:
$$
\hat e_3 = 
\frac{u_3}{\rvert u_3 \rvert}
$$