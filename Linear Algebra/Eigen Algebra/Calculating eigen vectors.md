---
Tags:
  - LinearAlgebra
  - Eigen
---


---

# 📘 Eigenvalues and Eigenvectors Step-by-Step Guide

Given a square matrix $A$, an **eigenvalue** λ and a corresponding **eigenvector** $\mathbf{v}$ satisfy:
$$
Av = \lambda \mathbf{v}

$$

This means applying the matrix A to v simply stretches or shrinks it — it doesn’t change the direction.

---

## 🧮 Step 1: Start with a Square Matrix

Let’s say we have a 2×2 matrix:

$A = \begin{bmatrix} 4 & 2 \\ 1 & 3 \end{bmatrix}$

---

## 🧾 Step 2: Set Up the Characteristic Equation

We need to solve the **characteristic equation**:
$$
det⁡(A−λI)=0
$$
Where $I$ is the identity matrix. For our example:
$$
A-\lambda I = \m{4-\lambda & 2 \\ 1 & 3-\lambda}
$$
$$
det(A-\lambda I) = (4-\lambda)(3-\lambda) -(2)(1)
$$

---

## 🧩 Step 3: Solve the Characteristic Polynomial

Now expand the determinant:

$(4 - \lambda)(3 - \lambda) - 2 = \lambda^2 - 7\lambda + 10$

Solve:

$\lambda^2 - 7\lambda + 10 = 0 (λ−5)(λ−2)=0(\lambda - 5)(\lambda - 2) = 0$

So the eigenvalues are:

$\lambda_1 = 5, \quad \lambda_2 = 2$

---

## 📐 Step 4: Find Eigenvectors

For each eigenvalue λ\lambda, solve:

$(A - \lambda I)\mathbf{v} = \mathbf{0}$

### 🔹 For λ=5\lambda = 5:

$A - 5I = \begin{bmatrix} -1 & 2 \\ 1 & -2 \end{bmatrix}$

Solve:

$\begin{bmatrix} -1 & 2 \\ 1 & -2 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} 0 \\ 0 \end{bmatrix}$

From the first row: $-x + 2y = 0 \Rightarrow x = 2y$

So the eigenvector is any scalar multiple of:

$\mathbf{v}_1 = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$

---

### 🔹 For λ=2\lambda = 2:

$A - 2I = \begin{bmatrix} 2 & 2 \\ 1 & 1 \end{bmatrix}$

Solve:

$2x + 2y = 0 \Rightarrow x = -y$

So the eigenvector is any scalar multiple of:

$\mathbf{v}_2 = \begin{bmatrix} -1 \\ 1 \end{bmatrix}$

---

## ✅ Final Answer

- Eigenvalues: $\lambda_1 = 5,\lambda_2 = 2$
    
- Corresponding Eigenvectors:
    
    - $\mathbf{v}_1 = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$
        
    - $\mathbf{v}_2 = \begin{bmatrix} -1 \\ 1 \end{bmatrix}$
        

---

![[Screenshot_20250510_135609_com_android_chrome_ChromeTabbedActivity.jpg]]
Trying it on 90° rotation
![[Screenshot_20250510_135916_com_android_chrome_ChromeTabbedActivity.jpg]]
