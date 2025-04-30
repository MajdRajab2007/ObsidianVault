## Solving the apples and bananas problem

$$
A^{-1} \times A = I
$$
Where  `I` is the Identity matrix (aka. the one that does nothing)

$$
 \newcommand\mycolv[1]{\begin{bmatrix}#1\end{bmatrix}}

\begin{bmatrix} 1&1&3 \\1&2&4\\1&1&2 \end{bmatrix}
\times
\mycolv{a\\b\\c} = \mycolv{15\\21\\13}
$$
And if you subtract the first row from row no.2 and no.3 in matrix 1 and the result vector you get: 
$$
 \newcommand\mycolv[1]{\begin{bmatrix}#1\end{bmatrix}}
\begin{bmatrix} 1&1&3 \\0&1&1 \\ 0&0&-1 \end{bmatrix} 
\times \mycolv{a\\b\\c} = \mycolv{15\\6\\-2}

$$
we multiply the last row by -1 
from which we find that 
$$
0\times15 + 0\times6+c = +2
$$
$$
c=2
$$
by doing that for all the matrices we find that we get a final set of matrices that is
$$
\begin{bmatrix} 1 & 0 & 0 \\0&1&0 \\0&0&1 \end{bmatrix} \times \mycolv{a\\b\\c} = \mycolv{5\\4\\2}
$$
so we did elimination to get the final row and then started taking row no.3 from row no.2 and so on until we got the final set which also resembles the identity matrix `I`

### Next: 
[[How to go from Gaussian elimination to finding the inverse of a matrix]]

___ 