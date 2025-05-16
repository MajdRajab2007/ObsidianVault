---
Tags:
  - LinearAlgebra
  - Matrices
---
To multiply two matrices, you use **matrix multiplication rules**, not element-wise multiplication. Here's a quick guide:

### ✅ **Matrix Multiplication Conditions:**

You can multiply matrix **A** by matrix **B** (**A × B**) **only if**:

- The **number of columns** in **A** equals the **number of rows** in **B**.
    

If:

- A is of size **m × n**
    
- B is of size **n × p**
    

Then:

- The result matrix **C = A × B** will have size **m × p**
    

---

### 🧮 **How to Multiply (Manually):**

For each entry $C_{ij}$  in the result matrix:

$\sum_{k=1}^{n} A_{ik} \cdot B_{kj}$


In words: take the **i-th row of A** and the **j-th column of B**, multiply the corresponding elements, and sum them.

---

### 🔢 **Example:**

Let:

$\begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}$

Then:

$A \times B = \begin{bmatrix} (1*5 + 2*7) & (1*6 + 2*8) \\ (3*5 + 4*7) & (3*6 + 4*8) \end{bmatrix} = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix}$

---

