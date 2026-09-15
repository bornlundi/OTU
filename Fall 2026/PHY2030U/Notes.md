# Chapter 1: Newton's Laws of Motion

## 1.1 Classical Mechanics

* Mechanics is the study of things that move, how things move, and why they move.
* Galileo and Newton laid the foundation on which Lagrange and Hamilton rendered their work simpler for practicing physicists.
* Classical mechanics branches off when:
  * Fast things are considered, we require **special relativity**.
  * Small things are considered, we require **quantum mechanics**.
  * Fast and small things are considered, it becomes **quantum field theory**.

## 1.2 Space and Time

* Newton's three laws of motion are formulated in terms of four crucial underlying concepts: space, time, mass, and force.

### Space

* Each point P of the 3-D space in which we live can be labeled by a position vector r that specifies a distance and direction of P from a chosen origin O.
* **r** = x**x** + y**y** + z**z**
* The non-bold symbols being the vector components.
* The bold symbols being the unit vectors.
* Other authors may use **i**, **j**, and **k** instead.
* You may even write simply:
  * **r** = (x, y, z).

### Vector Operations

* In our study, various operations can be performed with vector components.
* Given **r** = (r1, r2, r3) and **s** = (s1, s2, s3):
  * Their **sum** is **r** + **s** = (r1 + s1, r2 + s2, r3 + s3).
  * If *c* is a scalar and **r** is a vector, the product *c***r** is given by:
    * *c***r** = (*cr1*, *cr2*, *cr3*).
    * *c* affects the magnitude.
* There are two important kinds of products that can be formed by any pair of vectors.

#### Scalar Product (Dot Product)

* The scalar product, or **dot product**, of two vectors **r** and **s** is given by:

  **r** • **s** = rs cos θ = r1s1 + r2s2 + r3s3

* Here, *r* and *s* denote the magnitudes of the vectors **r** and **s**, and θ is the angle between them.
* The magnitude (length) of any vector **r** is denoted by |**r**|, which is the square root of the dot product of itself:

  |**r**| = √(**r** • **r**)

#### Vector Product (Cross Product)

* The other kind of product is the **vector product**, or **cross product**:

  **a** × **b** = |**a**| |**b**| sin θ **n**

### Time

* The classical view is that time is a universal parameter *t* on which all observers agree.

### Reference Frames

* Most problems involve a choice, explicit or implicit, of a **reference frame**. This is a choice of a spatial origin and axes to label positions, and a choice of temporal origin to measure times.
* In this course, we will touch on inertial and non-inertial frames only.

## 1.3 Mass and Force

* The concepts of mass and force are central to the formulation of classical mechanics.

### Mass

* Characterizes the object's inertia — its resistance to being accelerated.
* The agreed-upon unit is the kilogram.
* Mass is proportional to an object's weight if they are measured in the same location, so weighing is usually the easiest way to acquire mass.

### Force

* Informally understood as a push or pull.
* A unit of force is the Newton (N), defined as the magnitude of a force that accelerates a standard kilogram mass with an acceleration of 1 m/s².
* Forces have magnitudes and directions and are represented by vectors.
* If we apply a given force **F** to any object at rest, the direction of **F** is defined as the direction of the resulting acceleration, that is, the direction in which the body moves off.

## 1.4 Newton's First and Second Laws; Inertial Frames

### Newton's First Law (The Law of Inertia)

* In the absence of forces, a particle moves with constant velocity **v**.

### Newton's Second Law

* For any particle of mass *m*, the net force **F** on the particle is always equal to the mass *m* times the particle's acceleration:

  **F** = *m***a**

* Because the mass *m* of a particle never changes, we use **momentum**:

  **p** = *m***v**

* Thus, the second law may be rephrased to say that:

  **F** = d**p**/dt

### Differential Equations

* The first derivative of position with respect to time is velocity.
* The first derivative of velocity with respect to time is acceleration.
* Thus, the second integral of acceleration is position with respect to time.

### Inertial Frames

* When you drive past someone, they look like they are moving backwards, and you can obtain information about the motion of bodies by observing them from different frames.
* Inertial frames are simple when confined to small things on Earth. However, when Earth is your frame and you send a rocket through the air, Earth's rotation has real effects, especially when sending ships into space.

### Validity of the First Two Laws

* Though not universally true for all phenomena, the laws hold for all practical purposes to be exact when concerned with classical physics.
* Even as speeds reach *c* and relativity becomes important, the first law remains exactly true.
* In the classical domain, we can and shall assume that the first two laws are universally precise and valid. This will be our classical model.

## 1.5 The Third Law and Conservation of Momentum

* Every force on an object inevitably involves a second object — the object that exerts the force.
* Newton realized that if object 1 exerts a force on object 2, then object 2 always exerts a reaction force back on object 1. That force is always equal and opposite to the original force of object 1 on object 2.

### Newton's Third Law

* If object 1 exerts a force **F21** on object 2, then object 2 always exerts a reaction force **F12** on object 1 given by:

  **F12** = −**F21**

* As far as the total momentum of a system is concerned, the internal forces have no effect.
* If there are no external forces, **F**ext = 0, then the rate of change of momentum is 0.
* Thus, the important result is:

  * If **F**ext = 0, then **P** = const.
  * This result is called the principle of conservation of momentum.

### Principle of Conservation of Momentum

* If the net external force **F**ext on an N-particle system is zero, the system's total momentum **P** is constant.
* It is important to note that this would not hold at very high speeds because the idea of a single universal time is abandoned.
* Also, when it comes to charged particles, the resultant force is not always equal and opposite, somewhat negating the third law as well.

## 1.6 Newton's Second Law in Cartesian Coordinates

* The second law is what is mostly used to solve most simple problems.
* Conceptually, the simplest coordinate system is Cartesian with unit vectors **x**, **y**, and **z**, in terms of which the net force **F** can be written as:

  **F** = Fx**x** + Fy**y** + Fz**z**

* The position vector **r** can be written as:

  **r** = x**x** + y**y** + z**z**

* We see that Fx has to equal *m*ax, and similarly for the y and z components.

## 1.7 Two-Dimensional Polar Coordinates

* Instead of unit vectors **x** and **y**, we denote **r** as the unit vector that points in the direction we move when *r* increases, and **θ** as the unit vector that points in the direction we move when θ increases.
* This allows the net force **F** to be written as:

  **F** = Fr**r** + Fθ**θ**

* The rest of the chapter is an expansion on the derivative of the above equation and problem solving when an object is moving in circular paths.

