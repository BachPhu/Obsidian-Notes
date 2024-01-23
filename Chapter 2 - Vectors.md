# Vector Terminology

- A vector has: magnitude and direction
- _Resultant vector_: the sum of two or more vectors
- _Orthogonal_: vectors are at 90 degrees from one another
- _Anti-parallel_: vectors point in opposite directions (180 degrees apart).
![|400](https://openstax.org/apps/archive/20231109.173216/resources/b82f588387208ba48921020256bbddb5538f7f0f)

- [n] The letters θ and ϕ are often used to denote angles
![[Pasted image 20240122215906.png]]

---
# Three Dimensional Vectors

- We will solve most problems in two-dimensional or three-dimensional space.
- A coordinate system with directions, $x$, $y$, and $z$ can be represented by orthogonal unit vectors $i\hat{}$, $j\widehat{}$  , and $k\hat{}$, which are perpendicular to each other.
- These axes obey the relationship:
$$\hat{i} = \hat{j} \times \hat{k}$$

- A three-dimensional vector can be written in terms of its three components in these directions:
$$\vec{A} = A_{x}\hat{i} + A_{y}\hat{j} +  A_{z}\hat{k}$$
![[Pasted image 20240122220858.png]]

---
# Vector Construction

## Magnitude
- A two-dimensional vector that is horizontally and vertically aligned can be written as: 
$$\vec{A} = A_{x}\hat{i} + A_{y}\hat{j}$$
- Because these axes are perpendicular, the magnitude can be determined using the Pythagorean theorem:
$$|\vec{A}| =\sqrt{  A_{x}^{2} + A_{y}^{2} }$$

- In three-dimensions:
$$|\vec{A}| =\sqrt{  A_{x}^{2} + A_{y}^{2} + A_{z}^{2}}$$
## Direction
![[Pasted image 20240122222015.png]]

- The following trigonometric relationships can be used to relate the angle with the lengths of the triangle’s sides

> [!NOTE]
> $$sin \text{ }\theta = A_{y}/|\vec{A}|$$$$cos \text{ }\theta = A_{x}/|\vec{A}|$$
> $$tan \text{ }\theta = A_{y}/A_{x}$$

- Angle can be found from: 
$$\theta = cos^{-1}(A_{x}/|\vec{A}|)$$
$$\theta = sin^{-1}(A_{y}/|\vec{A}|)$$

> [!Main]
> $$\theta = tan^{-1}(A_{x}/A_{y})$$

---
# Vector Addition
- Given the following two vectors:
$$\vec{A} = A_{x}\hat{i} + A_{y}\hat{j} +  A_{z}\hat{k}$$ and
$$\vec{B} = B_{x}\hat{i} + B_{y}\hat{j} +  B_{z}\hat{k}$$

- Vectors can be added by adding each of the components:

$$\vec{A} + \vec{B} = (A_{x} + B_{x})\hat{i} + (A_{y} + B_{y})\hat{j} +  (A_{z} + B_{z})\hat{k}$$

![[Pasted image 20240122223044.png]]

---
# Scalar Multiplication and Subtraction

- Multiplication or division of a scalar will change the vectors magnitude but will not change the direction. Vectors can be multiplied with other vectors in two ways, using dot or cross products.

- This works by increasing or reducing each component, and the magnitude by the given factor:
$$c\vec{A} = cA_{x}\hat{i} + cA_{y}\hat{j} +  cA_{z}\hat{k}$$
$$|c\vec{A}| = |c||\vec{A}|$$
- Vectors can be subtracted by multiplying the second vector by negative one and then adding the two: 
$$\vec{A} - \vec{B} = \vec{A} + (-\vec{B}) = (A_{x} + -B_{x})\hat{i} + (A_{y} + -B_{y})\hat{j} +  (A_{z} + -B_{z})\hat{k}$$

![[Pasted image 20240122223747.png]]

---
# Unit Vectors

- A unit vector is a vector with a length of 1 and no units.
- Unit vectors only specify a direction.
- Unit vectors are denoted with the carrot ($\hat{v}$) instead of an arrow ($\vec{v}$) that is normally used for a vector.
- Any vector can be turned into a unit vector if you divide the magnitude of a vector from itself:
$$\hat{v} = \vec{v} / |\vec{v}|$$

The principal axes $\hat{i}$, $\widehat{j}$  , and $\hat{k}$ are an orthogonal set of unit vectors

![[Screen Shot 2024-01-22 at 10.51.08 PM.png]]

---
# The Dot Product

- The dot product of two vectors can be used as a measure of how much the vectors point in the same direction
- If you know the magnitude of the two vectors and ϕ, the angle between them, then the dot product is:
$$\vec{A} \cdot \vec{B} = |\vec{A}||\vec{B}|cos(\phi)$$
- If you know the Cartesian coordinates of the two vectors, then the dot product is:
$$\vec{A} \cdot \vec{B} = A_{x}B_{x} + A_{y}B_{y} + A_{z}B_{z}$$
- Dot products, more specifically combining both expressions, can be used to find the angle between two vectors
- This product always results in a scalar and the dot product is sometimes referred to as the scalar product.
![[Pasted image 20240122225626.png]]
![[Pasted image 20240122225630.png | 250]]

![[Pasted image 20240122225720.png]]

---
# The Cross Product

- The cross product is a vector quantity which will be oriented orthogonally (perpendicular) to both original vectors.

- It is possible to determine the magnitude of the resulting vector:
$$|\vec{A} \times \vec{B}| = |\vec{A}||\vec{B}|sin(\theta)$$
- The direction can be found using the “Right Hand Rule”
- This will have a maximum value when the vectors are perpendicular.
- This will have a minimum value of zero when the vectors are parallel

- The cross product can be determined by a determinant or the equivalent combination of vector components:

![[Screen Shot 2024-01-22 at 11.15.20 PM.png]]

- The order of the vectors used in the cross product is important because:

$$ \vec{A} \times \vec{B} = -\vec{B} \times \vec{A} $$
- Like the dot product, the cross product can also be used to determine the angle between two vectors.

---
# Vector Algebra Summary


![[Pasted image 20240122231658.png]]