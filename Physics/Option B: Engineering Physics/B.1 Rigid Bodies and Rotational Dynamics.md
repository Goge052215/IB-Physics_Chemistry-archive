# B.1 Rigid Bodies and Rotational Dynamics

## 1. Moment of Inertia

The moment of inertia ($I$) of a body is the rotational equivalent of the role played by mass in linear dynamics. Similarly to the inertial mass of an object being a measure of its opposition to a change in its motion, the moment of inertia of an object is its resistance to a change in its rotational motion.

In other words, the moment of inertia of an object quantifies its ability to resist changes to its rotational motion.

The moment of inertia of an object depends on the axis about which it is rotated. For a particle (a single point) mass $m$ rotating at a distance $r$ about an axis, the moment of inertia is given by:

$I = mr²$

Moments of inertia are scalar quantities and are measured in ($\text{kgm}^2$).

For an object consisting of more than one point mass, the moment of inertia about a given axis can be calculated by adding the moments of inertia for each point mass:

$I = \sum{mr²} = m_1r_1² + m_2r_2² + m_3r_3² + ... + m_nr_n²$

This summation is a mathematical abbreviation when the object comprises $n$ point masses.

The moment of inertia of a simple pendulum of length $l$ and mass $m$ is given by:

$I_{\text{pendulum}} = ml^2$

while a simple dumbbell consisting of two mass $m$ connected by a light rod with a length $l$, when rotating about the center of a rod, will be:

$I_{\text{dumbbell}} = m(\displaystyle \frac{l}{2})^2 + m(\frac{l}{2})^2 = 2m(\frac{l}{2})^2 = \frac {ml^2}{2}$

Note: In this case,‌ we assume the light rod has no mass

### Moment of inertia in 3-dimensional object

For three-dimensional solids, the formula must be derived for each special case. The moment of inertia for common solids of uniform density is given in the table below.

| Solid                                                                 | Preview                                                                                                                                                                                         | Moment of Inertia                     |
| :-------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------ |
| 1. A solid cylinder of mass m and radius r, rotating around its axis. | <img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.2.2-A-solid-cylinder-rotating-around-the-axis-through-its-centre.2ca4652917e0eef76dea.png" width="60" height="95"> | $I = \displaystyle \frac{1}{2} mr^2$  |
| 2. A disk of mass m and radius r, rotating around its axis.           | <img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.2.3-Solid-disk-rotating-around-its-centre.93f17d7a79428dc69f02.png?w=400&auto=compress" width="60" height="60">    | $I = \displaystyle \frac{1}{2} mr^2$  |
| 3. A solid sphere of mass m and radius r​, rotating around its axis.  | <img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.2.4-Solid-sphere-rotating-around-its-axis.73c5d0db5dc3c7225fff.png?w=400&auto=compress" width="60" height="90">    | $I = \displaystyle \frac{2}{5} mr^2$  |
| 4. Solid rod of mass m and length l,​ rotating around its center.     | <img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.2.5-Solid-rod-rotating-around-its-centre.025006cb647c37b021bb.png?w=500&auto=compress" width="80" height="40">     | $I = \displaystyle \frac{1}{12} ml^2$ |

### Example Questions - Inertia

**Q1:** Four equal masses of $100 \text{ g}$ are attached by light, rigid rods to form a square of side $20 \text{ cm}$. The square rotates around its center. What is its moment of inertia?

$m = 4 × 100\text{ g} = 0.4\text{ kg}$
$r = \frac{1}{2} × \sqrt{0.2^2 + 0.2^2} \text{ m} = 0.14\text{ m}$
$I = mr^2 = 0.008\text{ m}$

**Q2:** The moment of inertia of the Moon in its orbit around the Earth is $b×10^{40}\text{ kgm}^2$. What is the value of $b$? (The radius of the orbit is $3.9×10^5 \text{ km}$ and the mass of the Moon is $7.3×10^{22} \text{ kg}$)

$I = mr^2 = (7.3 × 10^{22}) × (3.9 × 10^5)^2 = 1.11 × 10^{40}\text{ kgm}^2$
$b = 1.11$

**Q3:** What is the moment of inertia of a solid disk of mass $1\text{ kg}$ and radius $1\text{ m}$?

$I = \displaystyle \frac{1}{2} mr^2 = \frac{1}{2} × 1 × 1^2 = 0.5\text{ kgm}^2$

## 2. Uniform motion in a circle

The body moves around a circle with a constant linear speed (or angular speed) and needs a centripetal force.

In all cases, the force providing the centripetal force will be given by:

$F = \displaystyle \frac{mv²}{r} = mω²r$

Where angular speed $ω$ is given by:

$ω = 2πf$

### Angular acceleration

Angular acceleration is the rate of change of angular speed with time.

$Δα = \displaystyle \frac{Δω}{Δt}$

$α$ is measured in radians per second squared ($\text{rad} s^{-2}$)

### Equations of motion

$v = u + at$
$s = ut + \displaystyle \frac{1}{2} at²$
$v² = u² + 2as$
$s = \displaystyle \frac{(v + u)t}{2}$

In rotational dynamics, four analogous equations apply to a body moving with constant angular acceleration:

$ω_f = ω_i + αt$
$θ = \displaystyle (ω_i)t + \frac{1}{2} αt²$
$ω_f² = ω_i² + 2αs$
$θ = \displaystyle \frac{1}{2}(ω_i + ω_f)t$

$v = ωr$
$a = αr$

Here,

$ω_i =$ initial velocity in ($\text{rad} \text{s}^{-1}$)
$ω_f =$ final velocity in ($\text{rad} \text{s}^{-1}$)
$θ =$ angular displacement in ($\text{rad}$) or sometimes ($°$)
$α =$ angular acceleration in ($\text{rad} \text{s}^{-2}$)
$t =$ time in ($s$).

### Graphs illustration

**θ-t, ω-t Graph:**

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.4.1-Graphs-of-angular-displacement-with-time-and-angular-velocity-with-time.396fb7c1e0e2cf670b7e.png?w=1200&auto=compress" width = "500" height = "300">

The table below shows the quantities that relate to the gradient and area under the graph for various graphs used to represent translational or rotational motion.

|  | s-t Graph | θ-t Graph | v-t Graph | ω-t Graph |
|:--|:--|:--|:--|:--|
| Gradient | Velocity | Angular Velocity | Acceleration | Angular Acceleration |
| Area under the graph | \ | \ | Displacement | Angular Displacement |

### Energy conservation

The formula of translational kinetic energy is:

$E_k = \displaystyle \frac{1}{2} × mv^2$

We can deduce the rotational kinetic energy from the formula of translational kinetic energy. Where we replace velocity $v$ with angular velocity $ω$ and mass $m$ with moment of inertia $I$:

$E_k = \displaystyle \frac{1}{2} × Iω^2$

**Important:** Often an object will have both rotational and translational kinetic energy. In the absence of any frictional force, the total mechanical energy will be conserved.

For example, consider an object rolling from rest down a smooth slope, changing its vertical height by a height $h$. The increased gravitational potential energy the object has at the top of the slope will be transformed into its rotational and translational kinetic energy at the bottom of the slope (the slope is smooth, so friction can be ignored). Applying the principle of conservation of energy:

$mgh = \displaystyle \frac{1}{2} × Iω^2 + \frac{1}{2} × mv^2$

where $m$ is the mass of the object, $I$ is its moment of inertia, and $ω$ and $v$ are the angular and linear velocity respectively at the bottom of the slope.

### Example Questions - Uniform Circular Motion

**Q1:** A wheel accelerates from rest with a constant angular acceleration of $1 \text{ rads}^{-2}$. Through what angle will the wheel have moved after 1 second?

$α = 1 \text{ rads}^{-2}$
$ω_i = 0$
$θ = \displaystyle (ω_i)t + \frac{1}{2} αt² = \frac{1}{2} \text{ rad}$

**Q2:** A wheel on a toy car accelerates at $0.11 \text{ ms}^{-2}$. If the wheel has a radius of $2.0 \text{ cm}$, what is its angular acceleration?

$a = αr$
$α = 0.11 / 0.02 = 5.5 \text{ rads}^{-2}$

**Q3:** The wheel of a bicycle is spinning with an angular velocity of $12 \text{ rads}^{-1}$ when the brakes are applied. The wheel makes 4 complete revolutions before coming to rest. What is the angular deceleration caused by applying the brakes?

$ω_f^2 = ω_i^2 + 2αθ$
$0 = 144 + 2α × 8π$
$α = \displaystyle \frac{144}{16π} = 2.9 \text{ rad}$

**Q4:** Calculate the rotational kinetic energy of a spinning top if it has the moment of inertia of $0.13 \text{kgm}^2$ and makes a complete revolution every 0.75 seconds.

$ω = \displaystyle \frac{2π}{0.75}= 8.4 \text{ rads}^{-1}$

$E_k = \displaystyle \frac{1}{2} × Iω^2 = \frac{1}{2} × 0.13 × 8.4 = 4.6 \text{ J}$

## 3. Torque

Torque ($Γ$) can be defined as the direction such that it makes an angle $θ$ to the radius of the circle in which the object rotates. In other words, Torque is the ability of a force to rotate an object.

The torque will be given by:

$Γ = Fr × \sin{θ}$

This is sometimes called the force multiplied by the "arm of the lever"

Torques are also called "moments', but to avoid confusion between "moment" and "momentum". They are vector quantities with the direction perpendicular to the plane. This rule also applies to the direction of angular displacement $θ$ and angular acceleration $α$.

The maximum torque that can apply to a body is when the force is perpendicular to the arm of the lever. In this case, $θ = 90°$ and so $\sin{θ} = 1$. This means that:

$Γ_{max} = Fr$

### Example Questions - Torque

**Q1**: A light, rigid rod of length $30 \text{ cm}$ is fixed to the wall so it protrudes horizontally. A $50 \text{ g}$ mass is suspended by a piece of string attached to the free end of the rod. What is the magnitude of the torque on the rod? Give your answer to two significant figures.

$r = 30 \text{ cm} = 0.3 \text{ m}$
$F = m = 50 \text{ g} = 0.05 \text{ kg} = 0.5 \text{ N}$\
$\therefore Γ = Fr = 0.3 × 0.05 = 0.15 \text{ Nm}$

**Q2**: Your hands are placed on opposite sides of a steering wheel of radius $12c \text{ cm}$. Each hand applies a constant force of $4.0 \text{ N}$ to the wheel, in opposite directions, starting perpendicular to the radius of the wheel. The direction of the force applied by the hands does not change (but does change relative to the wheel). What is the new torque after the steering wheel has been moved through an angle of $40°$?

$r = 12\text{ cm} = 0.12\text{ m}$
$F = 4.0\text{ N}$
$\therefore Γ = 2 × Fr × \sin{(90-θ)} = 0.12 × 2 × 4.0 × \sin{(90°-40°)} = 0.74 \text{ Nm}$

## 4. Equilibrium

### Translational & rotational equilibrium

- Translational equilibrium occurs when the resultant force on an object is zero.
- Rotational equilibrium occurs when the resultant torque on an object is zero.

If the rod was initially at rest, it must remain in translational and rotational equilibrium.

To be in translational equilibrium, the normal reaction force acting upwards from the pivot ($N$) must balance the weight of the hanging masses.

To be in rotational equilibrium, the overall torque should equal to 0:

$Γ_1 + Γ_2 = 0$

### Rotational KE and torque

Two more useful rotational analogies are given in the table below:

| Quantity | Linear Equation | Angular Equation |
|:--|:--|:--|
| Work ($W$) | $W = Fs$ | $W = Γθ$ |
| Power ($P$) | $P = Fv$ | $P = Γω$ |

### Worked example

A horizontal, rigid beam of length $2.3 \text{ m}$ and mass $8.3 \text{ kg}$ is fixed to a wall at one end, as illustrated in the figure below. A cable is attached to the other end and also fixed to the wall, making an angle of 26° to the rod. A mass of $43 \text{ kg}$ is placed on the beam, $1.9 \text{ m}$ from the wall. What is the tension in the cable?

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.3.2-Beam-fixed-to-a-wall.-A-cable-is-attached-to-the-other-end-and-a-mass-suspended-from-the-beam.914e02ca6fa623612db0.png?w=900&auto=compress" width="500" height="400">

### Solution

We will consider torques relative to the point where the beam meets the wall. We calculate the torque acting downwards and then use the rotational equilibrium definition to get the torque acting upwards from the tension from the string.

$Γ_{\text{mass}} = F_{\text{mass}}r' = m_{\text{mass}}gr' = 43\text{ kg} × 10 × 1.9\text{ m} = 800\text{ Nm}$
$\displaystyle Γ_{\text{rod}} = F_{\text{rod}}r = m_{\text{rod}}gr = 8.3\text{ kg} × 10 × \frac{2.3}{2} \text{ m} = 94\text{ Nm}$

$\sum Γ_{\text{Downward}} = Γ_{\text{mass}} + Γ_{\text{rod}} = 800 + 94 = 894\text{ Nm}$

Since the rod is in rotational equilibrium, the torque of the tension equals the sum of the torque from the rod and the mass.

$Γ_{\text{Tension}} = \sum Γ_{\text{Downward}} = 894\text{ Nm}$
$Γ_{\text{Tension}} = T × 2.3\text{m} × \sin{26°} = 894\text{ Nm}$

$\therefore T = 890\text{ N}$

### Example Questions - Equilibrium

**Q1:** Two children sit on a $1.5 \text{ m}$ long seesaw, which is pivoted at its center. The younger child, whose mass is $25 \text{ kg}$, sits at the furthest point on one side of the seesaw. The older child, whose mass is $41 \text{ kg}$, sits on the other side, ensuring that the seesaw balances. How close to the pivot is the older child?

$Γ_1 - Γ_2 = 0$\
$25\text{ kg} × 10 × 0.75\text{ m} = 41\text{ kg} × 10 × l$\
$l = 0.46\text{ m}$

**Q2:** A $15 \text{ kg}$ ladder rests against a smooth wall, making an angle of $47º$ to the horizontal. By considering the conditions for translational and rotation equilibrium, calculate the frictional force exerted on the ladder by the ground.

$F = W / \tan{47°} = 150\text{ N} / \tan{47°} = 140\text{ N}$
$\because Γ_F = Γ_f$
$\therefore F × l_{\text{ladder}} = f × 2l_{\text{ladder}}$
$f = \frac{1}{2} F = 70\text{ N}$

## 5. Rolling without sliding

Up to this point, we have drawn parallels between rotational motion and translational motion but largely treated them separately. Very often, however, objects will be undergoing both forms of motion simultaneously. Instead of just rotating around a fixed axis of rotation, they will be rolling.

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.7.1.d2712be8854b722deec1.png?w=1200&auto=compress" width = "500" height = "200">

- (a) A disk rotating about its center of mass
- (b) a disk sliding to the right
- (c) a disk rolling and sliding. In all cases, the red arrows represent the velocity of the disk at that point.

In Figure (a), a disk is rotating around its center of mass, with constant angular velocity $ω$. There is no translational motion, only rotational motion. Each point on the disk moves with velocity $ωr^′$ where $r^′$ is the distance from the point to the center of the disk. Points on the circumference move with velocity $ωr$ where $r$ is the radius of the disk. 

In Figure (b), the disk is moving to the right with constant velocity $v$. It is not rotating. This would be the motion expected if the disk was sliding across a surface. Every point on the disk is moving with velocity $v$, to the right.

If the disk rotates whilst sliding to the right, this is a **superposition** of the motion represented in Figures (a) and (b). The velocity of each point on the disk must be a combination of the rotational velocity $ωr^′$ and the translational velocity $v$. At the top of the disk, the rotational and translational velocities are in the same direction but at the bottom of the disk, whilst the translational velocity is to the right, the rotational motion gives a velocity to the left.

Figure (c) shows the linear velocity for different points on the disk.

The condition for an object to roll without slipping is that the point of contact with the surface has an instantaneous linear velocity of zero. This means that the velocity associated with the translational motion ($v$) is equal and opposite to the velocity associated with the rotational motion ($ωr$) at the point of contact. Under this condition, the velocity of the point at the top of the disk will be $2ωr$ to the right, as at this point the velocity associated with the translational motion and that from the rotational motion have equal magnitude and act in the same direction.

### Example Questions - Rolling without sliding

**Q1:** Consider a solid sphere of radius $5.0 \text{ cm}$ rolling down a slope of vertical height $47 \text{ cm}$. What is the angular velocity of the sphere at the bottom of the slope?

Consider energy conservation from $E_G$ to $E_k$:

$\displaystyle mgh = \frac{1}{2} × mv^2 + \frac{1}{2} × Iω^2$
$\displaystyle mg(0.47) = m (\frac{1}{2} × (ω^2r^2 + \frac{2}{5} × ω^2r^2)$
$0.47g = 0.00175 × ω^2$
$ω = 51 \text{ rads}^{-1}$

**Q2:** A solid circular coin of radius $1.0 \text{ cm}$ rolls down a slope of vertical height $1.0 \text{ m}$. What is the angular velocity of the coin at the bottom of the slope?

$\displaystyle mgh = \frac{1}{2} × mv^2 + \frac{1}{2} × Iω^2$
$\displaystyle mg = m (\frac{1}{2} × (ω^2r^2 + \frac{1}{2} × ω^2r^2)$
$g = 7.5 × 10^{-5} × ω^2$
$ω = 360 \text{ rads}^{-1}$

## 6. Rotational dynamics in Newton's 2nd Law

There is an equivalent form of Newton's Second Law which can be applied to rotational motion. Here, instead of the resultant force, we consider the resultant torque ($Γ$) and instead of mass, we use the moment of inertia ($I$). Newton's Second Law for rotational motion states that the angular acceleration($α$) is directly proportional to the resultant torque:

$Γ = Iα$

### Worked example

A sphere of mass $1.8 \text{ kg}$ and radius $12 \text{ cm}$ rolls (without slipping) down a plane that is inclined at an angle $25°$ to the horizontal. What is the acceleration of the sphere down the plane?

### Solution

We first draw a diagram of forces acting on the sphere:

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/14.1.5.1.96374405365161f5cdd8.png?w=900&auto=compress" width = "500" height = "330">

$W = 1.8 \text{kg} × 10 = 18 \text{ N}$
$θ = 25°$

There is no translational motion perpendicular to the plane, so the forces with components in this direction must balance:

$N = mg \cos{θ}$

The forces parallel to the plane are not balanced as the sphere is accelerating down the plane. The resultant force parallel to the plane is $mg \sin{θ} − F_f$, where $F_f$ is the frictional force, so applying Newton's Second Law for translational motion ($F=ma$):

$mg \sin{θ} − F_f = ma$

Now consider the net torque around a horizontal axis through the center of the sphere. The line of action of the weight and the normal reaction force pass through this point, so they do not contribute to the resultant torque. Hence applying Newton's Second Law for rotational motion and remembering that the moment of inertia of a sphere of mass m and radius r is $\frac{2}{5} mr^2$.


$F_f × r = Iα$
$\displaystyle F_f × r = \frac{2}{5} mr^2 α$
$\displaystyle F_f × r = \frac{2}{5} mr^2 × \frac{a}{r}$

$\displaystyle F_f = \frac{2}{5} ma$

$mg \sin{θ} − \frac{2}{5}ma = ma$
$\displaystyle \therefore g × \sin{θ} = \frac{7}{5}ma$
$\displaystyle \therefore a = \frac{5}{7} g \sin{θ}$

$\therefore a = 3.0 \text{ ms}^{-2}$

## 7. Angular momentum

For a rigid object with moment of inertia $I$ rotating at angular velocity $ω$, the angular momentum $L$ is defined as:

$L = Iω$

The unit of angular momentum is $\text{kg m}^2 \text{s}^{−1}$.

In the case that the rotating object is a point mass at a distance $r$ from the axis of rotation, the equation becomes:

$L = (mr)^2ω = (mr)rω = mvr$

Angular momentum is conserved in the absence of a resultant torque on a body.

### Example Question - Angular Momentum

The torque on a body with a moment of inertia $0.52 \text{ kgm}^2$ varies with time according to the following graph:

<img src="https://kognity-prod.imgix.net/media/edusys_2/content_uploads/23584.848c66f50ae33aefe01a.png?w=1200&auto=compress" width = "500" height = "300">

If the body was originally at rest, what is its final angular velocity?

$\displaystyle ΔL = 5 × 5 × \frac{1}{2} = 12.5 = Iω$
$ω = 12.5 / 0.52 = 24.0 \text{ rads}^{-1}$

## Key Formulas

### Moment of inertia

$I = mr²$

$I_{\text{pendulum}} = ml^2$
$\displaystyle I_{\text{dumbbell}} = \frac {1}{2} ml^2$

$\displaystyle I_{\text{cylinder}} = \frac{1}{2} mr^2$
$\displaystyle I_{\text{disk}} = \frac{1}{2} mr^2$
$\displaystyle I_{\text{sphere}} = \frac{2}{5} mr^2$
$\displaystyle I_{\text{rod}} = \frac{1}{12} mr^2$

### Uniform motion in a circle

$ω_f = ω_i + αt$
$\displaystyle θ = (ω_i)t + \frac{1}{2} αt²$
$ω_f² = ω_i² + 2αs$
$\displaystyle θ = \frac{1}{2}(ω_i + ω_f)t$

$v = ωr$
$a = αr$

### Rotational kinetic energy

$\displaystyle E_k = \frac{1}{2} × Iω^2$
$\displaystyle mgh = \frac{1}{2} × Iω^2 + \frac{1}{2} × mv^2$

### Torque & Equilibrium

$Γ = Fr × \sin{θ}$
$Γ = Iα$

$\sum Γ = 0$

$W = Γθ$
$P = Γω$

### Angular momentum

$L = Iω$
$L = (mr)^2ω = (mr)rω = mvr$
