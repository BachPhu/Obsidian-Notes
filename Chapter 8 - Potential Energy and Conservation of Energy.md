---
tags:
  - phy2048
---

8.1 Potential Energy of a System

8.2 Conservative and Non-Conservative Forces

8.3 Conservation of Energy

8.4 Potential Energy Diagrams and Stability

8.5 Sources of Energy

---
# 8.1 Potential Energy

- Potential energy can be thought of as stored energy that results from interactions between multiple objects.
- Unlike kinetic energy it is not defined for a single object.
- Potential energy cannot be defined absolutely, instead it is only defined relative to something else.
- When evaluating energy conservation changes in kinetic and potential energies are typically used.

- The force can be of various types, but typically it will be either
	- spring-like: $F_{x}= -kx$, and therefore $U(x) = \frac{1}{2}kx^{2}$ given U = 0 at the equilibrium position, x = 0
	- gravity-like with: F_y=-mg, and therefore $U(y)=mgy$ given U=0 at some reference height y = 0.

---
# 8.2 Conservative and Non-Conservative Forces

_Gravitational force_ and _spring force_ are _conservative forces_. The work done by a conservative force is independent of the path; in other words, the work done by a conservative force is the same for any path connecting two points:

Equivalently, a force is conservative if the work it does around any closed path is zero:

_Non-conservative forces_ are dissipative forces such as friction or air resistance. These forces take energy away from the system as the system progresses, energy that you can’t get back. These forces are path dependent; therefore it matters where the object starts and stops.

---
# 8.3 Conservation of Energy

The mechanical energy E of a particle stays constant unless forces outside the system or non-conservative forces do work on it, in which case, the change in the mechanical energy is equal to the work done by the non-conservative forces:
$$E = U + K$$
- In most situations, we will assume that energy losses are negligible and then relate the initial and final total mechanical energies:
$$\sum\limits K_{i} + \sum\limits U_{i} = \sum\limits K_{f} + \sum\limits U_{f}$$
or
$$\sum\limits K_{i} - \sum\limits K_{f} + \sum\limits U_{i} - \sum\limits U_{f} =0$$

---


![[Pasted image 20240308015055.png]]

As long as there is no friction or air resistance

$$\Delta K_{AB} = - \Delta U_{AB}$$

---

## Problem-Solving Strategy (Conservation of Energy)
1. Identify the body or bodies to be studied (the system). Often, in applications of the principle of mechanical energy conservation, we study more than one body at the same time.

2. Identify all forces acting on the body or bodies.

3. Determine whether each force that does work is conservative(Ei=Ef). If a non-conservative force (e.g., friction) is doing work, then mechanical energy is not conserved. The system must then be analyzed with nonconservative work.

4. For every force that does work, choose a reference point and determine the potential energy function for the force. The reference points for the various potential energies do not have to be at the same location.

1. Apply the principle of mechanical energy conservation by setting the sum of the kinetic energies and potential energies equal at every point of interest.

---
## Simple Pendulum

A particle of mass m is hung from the ceiling by a massless string of length 1 m. The particle is released from rest, when the angle between the string and the downward vertical direction is 30°. What is its speed when it reaches the lowest point of its arc? (Neglect air resistance in the problem)

$\sum\limits K_{i} + \sum\limits U_{i} = \sum\limits K_{f} + \sum\limits U_{f}$ → $0 + mgh = \frac{1}{2}mv^{2}+0$ 
$v = \sqrt{2gh}$        $v = \sqrt{2gl(1-cos\theta)}$ 
![[Pasted image 20240308015532.png]]
![[Pasted image 20240308015535.png]]

---
# 8.4 Stability and turning points
![[Screen Shot 2024-03-08 at 1.56.16 AM.png]]

## Potential energy diagram

For an object, *freely falling vertically*, near the surface of Earth, in the absence of air resistance.
![[Pasted image 20240308015654.png]]
At the maximum height

K = 0                  speed = 0

if the object were initially traveling upward, its velocity would go through zero there, and would be a *turning point* in the motion.  y max = E/mg


For a mass-spring system on a frictionless, horizontal surface
![[Pasted image 20240308015734.png]]
![[Screen Shot 2024-03-08 at 1.57.43 AM.png]]

---
Stable equilibrium is one which the force will accelerate the object back toward the equilibrium position.

(U(x) has a relative minimum there)
![[Pasted image 20240308015809.png]]
An unstable equilibrium will have forces that tend to accelerate an object away from equilibrium.

(U(x) has a relative maximum there)
![[Pasted image 20240308015825.png]]