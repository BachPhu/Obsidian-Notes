# 3.1 Position, Displacement, and Average Velocity

> [!Learning Objectives]
> - Define position, displacement, and distance traveled.
> - Calculate the total displacement given the position as a function of time.
> - Determine the total distance traveled.
> - Calculate the average velocity given the displacement and elapsed time.

## Displacement and Position
- The displacement is the change in position, in one dimension this is:
$$\Delta x = x_{f} - x_{i} $$
and equivalently: 
$$ x_{f} =  \Delta x  + x_{i} $$

- The total displacement for a trip is the sum of displacements between intermediate points.

- [9] $\Delta x_{total}= \sum\limits\Delta x_{i}$, for consecutive, non-overlapping points.

![[Screen Shot 2024-01-25 at 11.12.40 PM.png|300]]


## Average Velocity

- The average velocity which only depends on the endpoints (not the path) is given by:
$$\vec{v}_{avg} = \frac{\Delta\vec{r}}{\Delta t}$$


---

# 3.2 Instantaneous Velocity and Speed

> [!Learning Objectives]
> - Explain the difference between average velocity and instantaneous velocity.
> - Describe the difference between velocity and speed.
> - Calculate the instantaneous velocity given the mathematical equation for the velocity.
> - Calculate the speed given the instantaneous velocity.

## Instantaneous Velocity

- We can find the velocity of the object anywhere along its path by using some fundamental principles of calculus: 
$$\vec{v}_{inst}= \frac{d\vec{r}}{dt} = \lim_{\Delta t → 0} \frac{\vec{r}(t+\Delta t)-\vec{r}(t)}{\Delta t}$$
- The instantaneous velocity is the slope at any point in time on a position versus time plot.


- In one-dimension the instantaneous velocity is:
$$v_{x}=\frac{d}{dt}x(t)$$
![[Screen Shot 2024-01-25 at 11.11.24 PM.png]]
## Speed

- In physics, speed and velocity do not have the same meaning and are distinct concepts. One major difference is that speed has no direction; that is, speed is a scalar.
$$\text{Average speed = }\frac{\text{Total distance}}{\text{Elapsed time}}$$
Average speed is not necessarily the same as the magnitude of the average velocity, which is found by dividing the magnitude of the total displacement by the elapsed time

- However, we can calculate the instantaneous speed from the magnitude of the instantaneous velocity:              
$$ \text{Instantaneous speed = |v(t)|}$$

---

# 3.3 Average and Instantaneous Acceleration

> [!Learning Objectives]
> - Calculate the average acceleration between two points in time.
> - Calculate the instantaneous acceleration given the functional form of velocity.
> - Explain the vector nature of instantaneous acceleration and velocity.
> - Explain the difference between average acceleration and instantaneous acceleration.
> - Find instantaneous acceleration at a specified time on a graph of velocity versus time.

- Acceleration is the rate of change of velocity. $(m/s^2)$
- [8] The average acceleration is defined as:
$$\vec{a}_{avg}= \frac{\Delta \vec{v}}{\Delta t}$$
- Acceleration occurs when velocity changes in magnitude (an increase or decrease in speed) or in direction, or both.
- [8] The instantaneous acceleration is related to: 
$$\vec{a}_{inst}= \frac{d^{2}\vec{r}}{dt^{2}} = \lim_{\Delta t → 0} \frac{\vec{v}(t+\Delta t)-\vec{v}(t)}{\Delta t}$$
## Using derivatives in kinematics

- The kinematic equations allow for the acceleration as a function of time to be determined from the position as a function of time:
$$\vec{a}_{inst}= \frac{d^{2}\vec{r}}{dt^{2}}$$
- And more directly, $\vec{a}(t)$ is the time derivative of $\vec{v}(t)$:
$$\vec{a}_{inst}= \frac{d\vec{v}}{dt}$$
![[Screen Shot 2024-01-25 at 11.10.20 PM.png]]

---

![[Screen Shot 2024-01-25 at 11.16.33 PM.png]]
![[Screen Shot 2024-01-25 at 11.17.13 PM.png]]

---
# 3.4 Motion with Constant Acceleration

> [!Learning Objectives]
> - Identify which equations of motion are to be used to solve for unknowns.
> - Use appropriate equations of motion to solve a two-body pursuit problem.

## Displacement and Position from Velocity
- Taking the initial time to be zero, as if time is measured with a stopwatch, is a great simplification
![[Pasted image 20240125231854.png]]
where the subscript 0 denotes an initial value and the absence of a subscript denotes a final value in whatever motion is under consideration

- Since acceleration is constant, the average and instantaneous accelerations are equal
$$\bar{a} = a = \text{constant}$$
---
- [8] Average velocity when acceleration is constant:
$$\bar{v}=\frac{v_{0} + v}{2}$$
![[Screen Shot 2024-01-25 at 11.22.47 PM.png]]
![[Screen Shot 2024-01-25 at 11.22.29 PM.png]]

## Solving for Final Velocity from Acceleration and Time
- The x component of velocity of as a function of time for an object undergoing a constant x direction acceleration is given by:
$$a_{x} = \frac{v_{x} - v_{0}}{t}$$

> [!Constant acceleration]
> $$v_{x}(t)= a_{x}t + v_{0x}$$

- Final velocity depends on how large the acceleration is and how long it lasts
- If the acceleration is zero, then the final velocity equals the initial velocity ($v = v_{0}$), as expected (in other words, velocity is constant)
- If a is negative, then the final velocity is less than the initial velocity
## Solving for Final Position with Constant Acceleration

> [!NOTE]
> $$x(t) = \frac{1}{2}at^{2} + v_{0}t + x_{0}$$

- If acceleration is zero, then initial velocity equals average velocity, and

> [!NOTE]
> $$x(t) =  v_{0}t + x_{0} $$

motion with constant velocity (acceleration = zero)

- By solving for time in one equation and plugging the result into the other equation it can be determined that:

> [!NOTE]
> $$v^{2} = v^{2}_{0}+ 2a\Delta x$$


![[Pasted image 20240125233407.png]]

---
