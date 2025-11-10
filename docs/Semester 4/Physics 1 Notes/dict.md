# Physics 1 Dictionary
## Measuring Things
- #Changing-Units
  - $$\frac{1\text{ min}}{60s}=\frac{60s}{1\text{ min}}=1$$
  - We can multiply ratios by other ratios that equal 1 to change the units of an answer.
- #Density
  - Density is the mass (kg) per volume (m^3)
  - $$\rho = \frac{m}{V}$$
## Position, Displacement, and Average Velocity
- #Position-and-Displacement
  - A number line has an origin, positive direction, and negative direction.
  - Position is determined on this axis.
  - Displacement is a #Vector-Quantity on this axis.
- #Vector-Quantity
  - A quantity that has both a direction *and* magnitude, for example 15km east.
  - $$\vec{v}$$
- #Average-Velocity
  - The change in position over time x(t), also the slope of a straight line that connects two points on the graph of x(t) or the position relative to time.
  - $$v_{avg}=\frac{\Delta x}{\Delta t}=\frac{x_2-x_1}{t_2-t_1}$$
- #Average-Speed
  - The average speed includes *total* distance covered instead of the difference between point A and point B.
  - $$s_{avg}=\frac{\text{total distance}}{\Delta t}$$
- #Instantaneous-Velocity
  - "Average velocity/speed" is not helpful in most applications, an instant velocity can be found by making the two points closer and closer until they are practically the same.
  - $$v=\lim_{\Delta t \to 0}\frac{\Delta x}{\Delta t}=\frac{dx}{dt}$$
- #Average-Acceleration
  - The change in velocity over time, or the slope of v(t).
  - $$a_{avg}=\frac{\Delta v}{\Delta t}$$
- #Instantaneous-Acceleration
  - Similarly to #Instantaneous-Velocity, average acceleration is not as helpful, and the acceleration at a point is more important.
  - $$a=\frac{dv}{dt}=\frac{d^2x}{dt^2}$$
- #Constant-Acceleration
  - Most things in nature have constant acceleration like gravity.
  - When acceleration is constant, velocity is predictable:
    - $$v=v_0+at$$
  - When velocity is growing linearly, position can be found as:
    - $$v_{avg}=\frac{1}{2}(v_0+v)$$
    - Therefore:
    - $$x-x_0=v_0t+\frac{1}{2}at^2$$
  - Time is unknown:
    - $$v^2=v_0^2+2a(x-x_0)$$
  - Acceleration is unknown:
    - $$x-x_0=\frac{1}{2}(v_0+v)t$$
  - Starting velocity is unknown:
    - $$x-x_0=v_t-\frac{1}{2}at^2$$
- #Constant-Acceleration-Formulas
  - Formulas to solve for a given unknown **ASSUMING CONSTANT ACCELERATION**


| Formula 	| DeltaX 	| a 	| vf 	| vi 	| t 	|
|---	|---	|---	|---	|---	|---	|
| $$v=v_i+at$$ 	|  	| y 	| y 	| y 	| y 	|
| $$\Delta x=\bar{v}t=\frac{1}{2}(v_i+v_f)t$$ 	| y 	|  	| y 	| y 	| y 	|
| $$\Delta x=v_it+\frac{1}{2}at^2$$ 	| y 	| y 	|  	| y 	| y 	|
| $$v^2=v_i^2+2a(\Delta x)$$ 	| y 	| y 	| y 	| y 	|  	|


## Vectors
- #Scalar
  - A scalar has magnitude only, no direction.
- #Vector
  - A vector is a quantity with magnitude and direction.
  - Any vector has components in two-dimensional coordinate axes given as:
    - $$a_x=a\cos\theta \text{  and  } a_y=a\sin\theta$$
  - A vectors magnitude can be expressed as:
    - $$a=\sqrt{a_x^2+a_y^2} \text{  and  } \tan\theta=\frac{a_y}{a_x}$$
- #Unit-Vector
  - A unit vector is a vector with a magnitude of 1 and points in a direction along a single axis.
  - Unit vector notation in 3d space:
    - $$x+=\hat{i},\hspace{0.2cm}y+=\hat{j},\hspace{0.2cm}z+=\hat{k}$$
  - Can express a vector as a scalar (coordinate) and unit vectors.
    - $$\vec{a}=a_x\hat{i}+a_y\hat{j}+a_z\hat{k}$$
- #Vector-Addition
  - Vectors can be added geometrically by drawing them head-to-tail and connecting the first tail to the last head with a new vector.
  - Vectors can also be added by components:
    - $$\vec{r}=\vec{a}+\vec{b}$$
    - Therefore (works with others as well):
    - $$r_x\hat{i}=a_x\hat{i}+b_x\hat{i}$$
- #Vector-Multiplication
  - Multiplying a #Vector by a #Scalar, we get a new vector with magnitude V*S. 
  - Multiplying a #Vector by a #Vector, we get a new vector with magnitude and direction relative to the inputs.
    - Dot product = ONLY a Scalar, no direction
      - $$\vec{a}\cdot\vec{b}=|a||b|\cos{\theta}$$
      - Real multiplication
      - $$\vec{a}\cdot\vec{b}=(a_x\hat{i}+a_y\hat{j}+a_z\hat{k})(b_x\hat{i}+b_y\hat{j}+b_z\hat{k})$$
      - You only need to multiply terms with equal unit vectors, because ij=0, ik=0, jk=0.
      - $$\vec{a}\cdot\vec{b}=a_xb_x+a_yb_y+a_zb_z$$
    - Cross product = VECTOR product
      - $$\vec{a}\times\vec{b}=ab\sin{\theta}$$
      - Points in the direction of right hand rule, non-commutative (axb=-(bxa))
      - $$\vec{a}\times\vec{b}=(a_yb_z-b_ya_z)\hat{i}+(a_zb_x-b_za_x)\hat{j}+(a_xb_y-b_xa_y)\hat{k}$$
      - The reason the i component is (ay x bz - by x az) is because jxk=i but kxj = -i, so to get the full i components you need to consider the positive and negative i's.
- #Position-Vector
  - A particle's position can be given as a position vector r extending from a reference point (origin)
    - $$\vec{r}=x\hat{i}+y\hat{j}+z\hat{k}$$
  - Where x, y, and z are the magnitudes (scalars) and when multiplied by i, j, and k, you get the vector quantities.
- #Vector-Position-Change
  - $$\Delta\vec{r}=\vec{r}_2-\vec{r}_1$$
  - Unit-vector notation
  - $$\Delta\vec{r}=(x_2-x_1)\hat{i}+(y_2-y_1)\hat{j}+(z_2-z_1)\hat{k}$$
  - or
  - $$\Delta\vec{r}=\Delta x\hat{i}+\Delta y\hat{j}+\Delta z\hat{k}$$
## Projectiles
- #Projectile
  - A projectile is a particle moving in a vertical plane with some initial velocity *always* under the effects of *only* free-fall acceleration g, which is downward. It is "projected" therefore "projectile".
  - Given a launch angle, find horizontal and vertical components
    - $$v_{0x}=v_0\cos{\theta_0} \ \ \  and \ \ \ v_{0y}=v_0\sin{\theta_0}$$
- #Equations-of-Motion
  - Given a projectile (only g effecting it)
  - $$\Delta{x}=(v_0\cos{\theta_0})t$$
  - $$\Delta{y}=(v_0\sin{\theta_0})t-\frac{1}{2}gt^2$$
  - $$v_y=v_0\sin{\theta_0}-gt$$
  - $$v_y^2=(v_0\sin{\theta_0})^2-2g(\Delta{y})$$
- #Projectile-Trajectory
  - Given starting x and y positions are 0.
  - $$y=(\tan{\theta_0})x-\frac{gx^2}{2(v_0\cos{\theta_0})^2}$$
- #Projectile-Horizontal-Range
  - Horizontal distance from launch point at which the particle returns to the launch height.
  - $$R=\frac{v_0^2}{g}\sin{2\theta_0}$$
## Uniform Circular Motion
- #Circular-Motion
  - If a particle travels along a circle or arc of radius r at constant sped v, it is said to be in uniform circular motion and has acecleration of constant magnitude:
    - $$|\vec{a}|=\frac{v^2}{r}$$
  - The direction of which is towards the center of the circle, meaning it is centripetal.
  - The time it takes to complete a circle, or its period of revolution, is:
    - $$T=\frac{2\pi r}{v}$$
- #Centripetal-Force
  - The net centripetal force on a particle is directed toward the center of curvature of the particle's path.
    - $$F=\frac{mv^2}{R}$$
## Forces
- #Force
  - is the Push and Pull of an object. A force is a Vector with a magnitude and direction.
- #Newtons
  - is the measurement of #Force, about the weight force of a small apple, also known as a kg-m/s^2
- #Contact-Force
  - #Pushes
    - Friction, Normal.
  - #Pulls
    - Tension
- #Non-Contact-Force
  - The forces exerted by gravity, magnets, and electrostatic.
- #Freebody-Diagram
  - Drawing all #Force vectors acting on your object. Summing these gives you a #Net-Force.
- #Net-Force
  - The sum of all #Force vectors on an object, resulting in an acceleration if non-zero.
- #Normal-Force
  - A #Force directed perpendicular to the plane the object is exerting its force on.
- #Ideal-Banked-Turn
  - This equation is derived from splitting the normal force into its vertical (opposing gravity) and horizontal (turning) forces and simplifying.
    - $$\tan{\theta}=\frac{v^2}{gr}$$

## Friction
- #Kinetic-Friction
  - The opposing force to movement while two surfaces are sliding against each other and in motion.
  - $$f_k=\mu_mN$$
- #Static-Friction
  - The opposing force to movement while two surfaces are unmoving.
  - $$f_s\leq \mu_sN$$

## Energy
- #Energy
  - Is the capacity for something do do work. Measured in Joules.
  - Final energy is the initial plus the amount of work done on the object.
    - $$E_f=E_i+W$$
- #Work
  - Is a vector dot product, the amount of energy exerted on an object.
    - $$W=\vec{F}\Delta{\vec{x}}$$
  - The work of a *constant* force can be simplified to:
    - $$W=Fd\cos{\theta}$$
- #Power
  - The rate of work done on an object, measured in Watts or Joules/second.
    - $$P=\frac{W}{t}=Fv\cos{\theta}$$
- #Instantaneous-Power
  - The power at a moment in time.
  - $$P_{inst}=\frac{dW}{dt}=\vec{F}\cdot\vec{v}$$
- #Kinetic-Energy
  - The energy of a moving object. Increases/decreases based on net force on the object.
    - $$\text{KE}=\frac{1}{2}mv^2$$
- #Potential-Energy
  - The energy stored by a system such as gravity or a spring.
  - For gravity
    - $$PE_g=mgh$$
- #Conservation-of-Energy
    - $$KE_f+PE_f=KE_i+PE_i+W_{ext}$$
    - This is equivalent to
    - $$\frac{1}{2}mv_f^2+mgh_f=\frac{1}{2}mv_i^2+mgh_0+\vec{F}\cdot{\Delta{\vec{r}}}$$

## Springs
- #Spring-Constant
  - The "stiffness" of a spring that relates to its resistance to change.
    - $$F=-kx$$
    - Where F is the restoring force by the spring, k is the spring constant, and x is the displacement from equilibrium.
- #Spring-Work
  - The work done on an object by a spring is the area under the curve of the graph of force against displacement from equilibrium.
    - $$W_s=\frac{1}{2}kx_i^2-\frac{1}{2}kx_f^2$$

## Momentum
- #Momentum
  - The willingness of an object to maintain its movement or lack thereof.
  - Measured in kgm/s
  - $$\vec{p}=m\vec{v}$$
- #System-Momentum
  - Related to total sum mass and the center of mass's velocity.
  - $$\vec{P}=M\vec{v_{com}}$$
- #Linear-Momentum
  - If a system is closed and isolated such that no net external force acts on it, then the linear momentum must be constant regardless of internal changes.
  - $$\vec{P}_i=\vec{P}_f$$
- #Center-of-Mass
  - In a multi-particle system the center of mass will not be exactly in one particle, instead somewhere else.
  - $$\vec{r}_{com}=\frac{1}{M}\sum_{i=0}^{n}m_i\vec{r_i}$$
  - This follows from
  - $$x_{com}=\frac{m_1x_1+m_2x_2}{m_1+m_2}$$
- #Inelastic-Collision
  - When two inelastic bodies collide, the kinetic energy of the two-body system is not conserved, but if the system is closed and isolated, the total linear momentum *must* be conserved, such that:
    - $$\vec{p}_{1i}+\vec{p}_{2i}=\vec{p}_{1f}+\vec{p}_{2f}$$
- #Impulse
  - This is the change in momentum an object feels during a collision.
    - $$\vec{p}_f-\vec{p_i}=\Delta \vec{p}=\vec{J}$$
  - If you take the equation:
    - $$F=\frac{dp}{dt}$$
  - And solve for a change in p, you must find the area under the curve of F(t)
    - $$J=\Delta{p}=\int_{t_1}^{t_2}F\ dt$$
  - Side note, impulse is the integral of force over time, and work is the integral of force over displacement, very similar concept.
- #Integrals
  - I suppose we're learning integrals from prelecs for physics.
  - If you have a polynomial it is easy to integrate, just increase exponent by 1 and divide by the same number:
    - $$\int_{x_1}^{x_2}ax^2+bx=\left[ \frac{ax^3}{3}+\frac{bx^2}{2}\right]_{x_1}^{x_2}=(\frac{ax_1^3}{3}+\frac{bx_1^2}{2})-(\frac{ax_2^3}{3}+\frac{bx_2^2}{2})$$

## Rotation
- #Rigid-Body
  - An object is a rigid body if all parts of a body rotate around a fixed axis locked together.
- #Rotation-Angle
  - A full rotation is 1 revolution = 360deg = 2pi radians.
  - $$\theta=\frac{s}{r}$$
  - Where s = the arc length of a circular path of radius r and angle theta.
- #Angular-Velocity
  - An average velocity can be given by:
    - $$\omega_{avg}=\frac{\Delta\theta}{\Delta t}$$
  - Or, the instantaneous angular velocity can be given by:
    - $$\omega=\frac{d\theta}{dt}$$
  - These are both vectors, with directions given by a right-hand rule. Positive for counterclockwise and negative for clockwise.
- #Angular-Acceleration
  - Likened to translational acceleration, average angular acceleration is:
    - $$\alpha_{avg}=\frac{\Delta\omega}{\Delta t}$$
  - And instantaneous angular acceleration is:
    - $$\alpha=\frac{d\omega}{dt}$$
- #Constant-Angular-Acceleration
  - See #Constant-Acceleration for the full rundown, which applies word for word here with position replaced by theta, velocity replaced by omega, and acceleration replaced by alpha.
- #Angular-Linear-Variables
  - Linear Position
    - $$s=\theta r$$
    - where theta is in radians and r is the radius
  - Linear Velocity 
    - $$v=\omega r$$
    - where omega is the angular speed (rad/s)
  - Linear Acceleration
    - Tangential Component
      - $$a_t=\alpha r$$
      - where alpha is the angular acceleration
    - Radial Component
      - $$a_r=\frac{v^2}{r}=\omega^2r$$
  - Period
    - $$T=\frac{2\pi r}{v}=\frac{2\pi}{\omega}$$
- #Moment-of-Inertia
  - The closer the mass is to the center of mass, the lower the coefficient of I, relating to the ratio of energy converted to translational and 
  - Typically (for symmetric rotation objects) some constant (ratio of translational to rotational energy) times M(center of mass) R(radius) squared.
    - $$I=cMR^2$$
- #Rotational-Kinetic-Energy
  - $$KE_{rot}=\frac{1}{2}I\omega^2$$
    - Where I is the moment of inertia and omega is the rotational velocity.
- #COM-Velocity
  - $$V_{com}=\sqrt{(\frac{2}{k+1})gh}$$
    - Given that k is the coefficient of the moment of inertia and gh relates to the starting potential energy minus the ending potential energy.

| Formula 	| $$\Delta\theta$$ 	| $$\alpha$$ 	| $$\omega_f$$ 	| $$\omega_i$$ 	| t 	|
|---	|---	|---	|---	|---	|---	|
| $$v\omega=\omega_i+\alpha t$$ 	|  	| y 	| y 	| y 	| y 	|
| $$\Delta \theta=\bar{\omega}t=\frac{1}{2}(\omega_i+\omega_f)t$$ 	| y 	|  	| y 	| y 	| y 	|
| $$\Delta \theta=\omega_it+\frac{1}{2}\alpha t^2$$ 	| y 	| y 	|  	| y 	| y 	|
| $$\omega^2=\omega_i^2+2\alpha(\Delta \theta)$$ 	| y 	| y 	| y 	| y 	|  	|

## Wheel
- #Wheel-Velocity
  - $$v_{com}=\omega R$$
    - Where R is the radius of the wheel, omega is the angular speed of the wheel relative to radius R, and vcom is the linear speed of the wheel's center of mass.
- #Torque
  - A turning or twisting action due to a force F.
  - If a force is exerted at a point given by the position vector r relative to the axis, then the magnitude of the torque is
    - $$\tau=rF_t=r_{\perp}F=rF\sin(\phi)$$
    - Where F_t is the component of F perpendicular to r and phi is the angle between r and F. The quantity r_perp is the perpendicular distance between the rotation axis and an extended line running through the F vector. This line is called the line of action of F and r_perp is called the moment arm of F. Similarly, r is the moment arm of F_t
  - SI unit ise Newton-Meter, positive if it rotates a body right-hand and negative if left-hand.
- #Line-of-Action
  - The line of the force tangent to the radius of the object determines its angular acceleration. If you pull on a spool at an angle above and to the side, you can slide it without rolling it.

## Gravity
- #Gravity
  - $$F_{grav}=-G\frac{M_1M_2}{R^2}\vec{r}$$
    - Where G is 6.67E-11 with units to convert kg^2/m^2 to N
    - Negative indicating an attractive force, directed in r-hat indicating towards each other.
  - g (the 10m/s^2) is therefore GM/r^2 = ~10
- #Gravitational-Field
  - $$\vec{g}=\frac{\vec{F}}{m}=-G\frac{M}{r^2}\hat{r}$$
- #Gravitational-Potential
  - $$=V_g=-\frac{GM}{r}$$
- #Gravitational-Potential-Energy
  - $$E=mgh=-\frac{GMm}{r}$$

## Oscillators
- #Period
  - $$T=\frac{2\pi}{\omega}$$
  - Where, on a spring, omega is
    - $$\sqrt{\frac{k}{m}}$$
    - Where k=spring constant and m=mass of object
  - Where, on a simple pendulum, omega is
    - $$\sqrt{\frac{g}{R}}$$
    - Where g=gravity acceleration, and R is the length of the arm
- #Simple-Harmonic-Motion
  - Any time a system has a restoring force:
  - $$\frac{d^2x(t)}{dt^2}+\omega^2x(t)=0$$
  - Where x(t) is
    - $$x(t)=X_{max}\cos(\omega t+\Theta)$$
    - $$x'(t)=-\omega X_{max}\sin(\omega t+\Theta)$$
    - $$x''(t)=-\omega^2X_{max}\cos(\omega t+\Theta)$$
  - This shows that where the angular acceleration is max is where the position is lowest (sign is flipped), and angular velocity is the highest when position is 0.
  - Note that the theta is the phase angle.
