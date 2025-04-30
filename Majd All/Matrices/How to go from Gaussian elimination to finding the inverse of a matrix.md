We know that 
$$
A^{-1} \times A = I
$$
If we imagine a matrix of A and B written like:
$$
\begin{bmatrix} 1&1&1\\ 1& 2 &4 \\1&1&2 \end{bmatrix} \times \begin{bmatrix} b_{11} & b_{12} & b_{13} \\ b_{21} & b_{22} & b_{23} \\ b_{31} & b_{32} & b_{33} \end{bmatrix} = I = \begin {bmatrix} 1 & 0 & 0\\0&1&0 \\ 0&0&1 \end{bmatrix}
$$
by taking row no.1 from the row no.2 and row no.3 in both sides of the equation (i.e A and I) and multiplying the final row by -1
we get:
$$
	\m{1&1&3\\0&1&1\\0&0&1} = \m{1&0&0\\-1&1&0\\1&0&-1}
$$
then like the previous lesson ([[Gaussian elimination]]) :
$$
\m{1&1&0\\0&1&0\\0&0&1} = \m{-2&0&3\\-2&1&1\\1&0&-1}
$$
$$
\m{1&0&0\\0&1&0\\0&0&1} = \m{0&-1&2\\-2&1&1\\1&0&1} = A^{-1} = B
$$
$$
A\times A^{-1} = I
$$
### Next:
[[Determinants and inverses]]
___