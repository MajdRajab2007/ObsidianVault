---
aliases:
  - Special Eigen Cases
Tags:
  - LinearAlgebra
  - Eigen
---
In the context of eigenvalues and eigenvectors, there are three special cases to consider:

1. **Uniform Scaling**:
    
    - In this case, all vectors are eigenvectors because they are scaled by the same amount in every direction.
    - The eigenvalue represents the scaling factor.
2. **180-Degree Rotation**:
    
    - This rotation has eigenvectors that point in the opposite direction after the transformation.
    - All vectors are still eigenvectors, but they have an eigenvalue of -1, indicating they maintain their length but change direction.
3. **Combination of Shear and Scaling**:
    - This case is less obvious, as not all vectors are eigenvectors.
    - Some vectors, like the horizontal shear vector, remain unchanged (eigenvalue of 1), while others may not be eigenvectors despite the transformation having eigenvectors.
