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

## Friction
- #Kinetic-Friction
  - Relative motion of surfaces, easier to calculate.
  - $$f_k=\mu_mN$$

## Energy
- #Energy
  - Is the capacity for something do do work. Measured in Joules.
  - Final energy is the initial plus the amount of work done on the object.
    - $$E_f=E_i+W$$
- #Work
  - Is a vector dot product, the amount of energy exerted on an object.
    - $$W=\vec{F}\Delta{\vec{x}}$$
- #Kinetic-Energy
  - The energy of a moving object. Increases/decreases based on net force on the object.
    - $$\text{KE}=\frac{1}{2}mv^2$$
- See #Vector-Multiplication
