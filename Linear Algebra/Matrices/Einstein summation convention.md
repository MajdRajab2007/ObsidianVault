---
Tags:
  - LinearAlgebra
  - Matrices
---
When multiplying two arrays A and B, instead of multiplying each row and each column to  get a single element, we can use the formula: 
$$
\sum_j{a_{ij}}b_{jk} = {a_{ij}}b_{jk}
$$
*Note:* *the summation convention allows for the sum to be written without the $\sum$*

*Note:* ![[Photos/Pasted image 20250501162242.png]]

And this formula can be very useful when coding where you can loop over all J's then all the I's then all K's

This also allows us to multiply matrices that are not squares **Only if the rows from the left matrix is equal to the columns from the right one** as shown in the photo below: ![[Pasted image 20250501154613.png]]

However, the dot product is like multiplying two single line and single row columns 
$$
\mycolv{v_1\\v_2\\v_3\\ \dotsb} \times \mycolv{u_1\\u_2\\u_3\\\dotsb} = \m{v_1&v_2&v_3&\dots} \times \m{u_1\\u_2\\u_3\\\dotsb}
$$
and the geometrical proof is : ![[Pasted image 20250501160328.png]]
