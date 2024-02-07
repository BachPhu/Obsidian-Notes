---
quickshare-date: 2024-02-02 00:24:56
quickshare-url: https://noteshare.space/note/cls47b7dy1046001mwrxb23dq1#AnbCN9nbJWrsTY2x4Rn/gVTa1g7GVINasKa64Td/FUE
tags:
  - phy2048
share_link: https://share.note.sx/1yxukq2s#yS3u7IXSkQ+TNFBjRlIn4sUPeRNyP5UxLHmb4i3+KjA
share_updated: 2024-02-02T00:25:45-05:00
---

4.1 Displacement and Velocity Vectors

4.2 Acceleration Vector

4.3 Projectile Motion

4.4 Uniform Circular Motion

---
# 4.1 Displacement and Velocity Vectors

> [!Learning Objectives]
> - Calculate position vectors in a multidimensional displacement problem.
>  - Solve for the displacement in two or three dimensions.
> - Calculate the velocity vector given the position vector as a function of time.
> - Calculate the average velocity in multiple dimensions

## Displacement Vector

- In three-dimensions, the position vector is comprised from the individual components:
$$\vec{r}(t)= x(t)_{x}\hat{i} + x_{y}(t)\hat{j} + x_{z}(t)\hat{k}$$
- The displacement vector is the change between the position vector at two times
$$\Delta \vec{r} = \vec{r}(t_{2})- \vec{r}(t_{1})$$

---
## Velocity Vector

The velocity vector is similarly defined:
$$\vec{v}(t)= v(t)_{x}\hat{i} + v_{y}(t)\hat{j} +v_{z}(t)\hat{k}$$

---

## Independence of Motion
In the kinematic description of motion, we are able to treat the horizontal and vertical components of motion separately. In many cases, motion in the horizontal direction does not affect motion in the vertical direction, and vice versa.

![[Pasted image 20240201234614.png]]
A diagram of the motions of two identical balls: one falls from rest and the other has an initial horizontal velocity.

Each subsequent position is an equal time interval. Arrows represent the horizontal and vertical velocities at each position. The ball on the right has an initial horizontal velocity whereas the ball on the left has no horizontal velocity. Despite the difference in horizontal velocities, the vertical velocities and positions are identical for both balls, which shows the vertical and horizontal motions are independent.

---

# 4.2 Acceleration Vector

> [!Learning Objectives]
> - Calculate the acceleration vector given the velocity function in unit vector notation.
> - Describe the motion of a particle with a constant acceleration in three dimensions.
> - Use the one-dimensional motion equations along perpendicular axes to solve a problem in two or three dimensions with a constant acceleration.
> - Express the acceleration in unit vector notation.


$$\vec{a}(t)= a(t)_{x}\hat{i} + a_{y}(t)\hat{j} +a_{z}(t)\hat{k}$$

 Three-dimensional motion is equivalent to three one-dimensional motions, each along an axis perpendicular to the others.

 $$x(t) = \frac{1}{2}at^{2} + v_{0}t + x_{0}$$
(same thing for y and z axis)

$$v_{x}(t)=a_{x}t + v_{0x}$$
(same thing for y and z axis)
$$v^{2} = v^{2}_{0}+ 2a\Delta x$$
(same thing for y and z axis)

---
# 4.3 Projectile Motion

> [!Learning Objectives]
> - Use one-dimensional motion in perpendicular directions to analyze projectile motion.
> - Calculate the range, time of flight, and maximum height of a projectile that is launched and impacts a flat, horizontal surface.
> - Find the time of flight and impact velocity of a projectile that lands at a different height from that of launch.
> - Calculate the trajectory of a projectile.

Step 1: find initial velocity due to x and y axis
- The initial velocity components depend on the initial angle $θ_{0}$ and the initial velocity $v_{0}$:
$$v_{0x}= v_{0}cos(\theta _{0})$$
$$v_{0y}= v_{0}sin(\theta _{0})$$
Step 2: Plug initial velocity down these formula
- [6] Use this formula:  $$x(t) = \frac{1}{2}at^{2} + v_{0}t + x_{0}$$
- If the downward force from gravity is the only force on the object, then $a_{x}=0 \text{ and } a_{y}=-g$ such that:

> [!Formula for projectile motion]
> $$x(t) = \frac{1}{2}at^{2} + v_{0}t + x_{0}$$
> $$y(t) = \frac{1}{2}at^{2} + v_{0}t + y_{0}$$
> $$v_{y}(t) = -at + v_{0y}$$


![[Screen Shot 2024-02-02 at 12.04.49 AM.png]]

---
## Trajectory
![[Screen Shot 2024-02-07 at 2.08.59 AM.png]]

![[Screen Shot 2024-02-02 at 12.09.14 AM.png]]

---
# 4.4 Uniform Circular Motion


> [!Learning Objectives]
> - Solve for the centripetal acceleration of an object moving on a circular path.
> - Use the equations of circular motion to find the position, velocity, and acceleration of a particle executing circular motion.
> - Explain the differences between centripetal acceleration and tangential acceleration resulting from nonuniform circular motion.
> - Evaluate centripetal and tangential acceleration in nonuniform circular motion, and find the total acceleration vector.

## Circular motion terminology

- An objects moving in circular motion have can have their position, velocity, and acceleration parameterized as a function of time:

$$\vec{r}(t) = A\text{ cos } \omega \text{ t } \hat{i} + A\text{ sin } \omega \text{ t } \hat{j}$$
$$\vec{v}(t) = \frac{d \vec{r}(t)}{dt} = - A\text{ sin } \omega \text{ t } \hat{i} + A\text{ cos } \omega \text{ t } \hat{j}$$
$$\vec{a}(t) = \frac{d \vec{v}(t)}{dt} = - A\text{ cos } \omega \text{ t } \hat{i} - A\text{ sin } \omega \text{ t } \hat{j}$$

- The angular frequency and period are all related by:
ω=2 π 
f=2 π/T

---

## Uniform Circular Motion

- Motion is uniform if the speed is constant.
- For uniform circular motion there is a change in velocity, i.e., acceleration, that is radially inward.
- This can be seen using either the instantaneous or average velocities.
- The constant transverse speed is related to the period and angular frequency:
$$|\vec{v}| = \frac{2 \pi |\vec{r}|}{T} = |\vec{\omega}| |\vec{r}| $$
- The centripetal acceleration is also related to the speed and radius:
$$|\vec{a}_{c}| = \frac{|\vec{v}|^{2}}{\vec{r}} = |\vec{\omega}|^{2} |\vec{r}| $$![[Screen Shot 2024-02-02 at 12.18.35 AM.png]]

---

## Non-Uniform Circular Motion

- Motion is non-uniform if the speed changes:
$$|\vec{a}_{t|}= \frac{d|\vec{v}|}{dt}$$
- If the motion is non-uniform and circular then there are two non-zero components of the acceleration, which are perpendicular to each other.
	- The tangential component of the acceleration is due to changing speed.
	- The centripetal component of the acceleration is due to changing direction.

- Total acceleration can be found from these components:

$$\vec{a}_{tot}= \vec{a}_{t} + \vec{a}_{c} = \vec{a}_{丄}+ \vec{a}_{r} = \frac{d|\vec{v}|}{dt} \hat{v} = \frac{|\vec{v}|^{2}}{\vec{r}} \hat{r}$$