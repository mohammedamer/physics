# Physics Cheat Sheet

# Mechanics

## Physics and Measurement
- SI base quantities: length, mass, and time.
- Derived quantities often come from dimensional combinations of base units.
- Use dimensional analysis, unit conversions, significant figures, and order-of-magnitude estimates constantly.

$$
\rho = \frac{m}{V}
$$

## Motion in One Dimension
- Displacement, velocity, and acceleration define 1D kinematics.
- Average speed is total distance over total time.
- Free fall uses constant acceleration $a = -g$ if upward is positive.

$$
\Delta x = x_f - x_i
$$

$$
v_{\text{avg}} = \frac{\Delta x}{\Delta t},
\qquad
v = \frac{dx}{dt}
$$

$$
a_{\text{avg}} = \frac{\Delta v}{\Delta t},
\qquad
a = \frac{dv}{dt} = \frac{d^2x}{dt^2}
$$

$$
v_f = v_i + at
$$

$$
x_f = x_i + v_i t + \frac{1}{2}at^2
$$

$$
v_f^2 = v_i^2 + 2a(x_f - x_i)
$$

$$
x_f - x_i = \frac{1}{2}(v_i + v_f)t
$$

## Vectors
- Scalars have magnitude only; vectors have magnitude and direction.
- Resolve vectors into components and combine them componentwise.

$$
|A| = \sqrt{A_x^2 + A_y^2}
$$

$$
\hat{u} = \frac{A}{|A|}
$$

$$
A = A_x \hat{i} + A_y \hat{j} (+ A_z \hat{k})
$$

$$
A \cdot B = AB \cos \theta = A_x B_x + A_y B_y + A_z B_z
$$

## Motion in Two Dimensions
- Treat $x$- and $y$-motion independently.
- Projectile motion combines constant horizontal velocity with vertical free fall.
- Circular motion requires radial acceleration.

$$
x = v_0 \cos \theta \, t
$$

$$
y = v_0 \sin \theta \, t - \frac{1}{2}gt^2
$$

$$
v_x = v_0 \cos \theta,
\qquad
v_y = v_0 \sin \theta - gt
$$

$$
a_r = \frac{v^2}{r} = \omega^2 r
$$

$$
v_{A/C} = v_{A/B} + v_{B/C}
$$

## The Laws of Motion
- Newton's first law describes motion with zero net force.
- Newton's second law connects force and acceleration.
- Newton's third law pairs interaction forces.
- Friction depends on the normal force.

$$
\sum F = ma
$$

$$
W = mg
$$

$$
f_s \le \mu_s N,
\qquad
f_k = \mu_k N
$$

## Circular Motion and Other Applications of Newton's Laws
- Uniform circular motion requires an inward net force.
- Accelerated frames can introduce apparent forces.
- Resistive forces are often modeled as proportional to $v$ or $v^2$.

$$
\sum F_r = \frac{mv^2}{r}
$$

$$
\tan \theta = \frac{v^2}{rg}
$$

$$
f = -bv
\qquad \text{or} \qquad
f = -cv^2
$$

## Energy and Energy Transfer
- Work transfers energy into or out of a system.
- The work-kinetic energy theorem links net work and kinetic energy.
- Power is the rate of doing work.

$$
W = Fd \cos \theta
$$

$$
W = \int F_x \, dx
$$

$$
K = \frac{1}{2}mv^2
$$

$$
W_{\text{net}} = \Delta K
$$

$$
P_{\text{avg}} = \frac{\Delta W}{\Delta t},
\qquad
P = \frac{dW}{dt} = F \cdot v
$$

$$
\Delta E_{\text{system}} = T + W + Q
$$

## Potential Energy
- Conservative forces are associated with potential energy.
- Mechanical energy is conserved in isolated systems with only conservative forces.
- Stable equilibrium occurs near minima of the potential-energy curve.

$$
U_g = mgy
$$

$$
U_s = \frac{1}{2}kx^2
$$

$$
K_i + U_i = K_f + U_f
$$

$$
F_x = -\frac{dU}{dx}
$$

## Linear Momentum and Collisions
- Momentum is conserved in isolated systems.
- Impulse equals the change in momentum.
- Collisions are analyzed with momentum conservation, and sometimes with energy conservation.

$$
p = mv
$$

$$
J = \int F \, dt = \Delta p
$$

$$
\sum p_i = \sum p_f
$$

$$
r_{\text{cm}} = \frac{\sum m_i r_i}{\sum m_i},
\qquad
v_{\text{cm}} = \frac{\sum m_i v_i}{\sum m_i}
$$

$$
\Delta v = v_e \ln \left(\frac{m_i}{m_f}\right)
$$

## Rotation of a Rigid Object about a Fixed Axis
- Angular kinematics mirrors linear kinematics.
- Torque is the rotational analog of force.
- Rolling without slipping ties translational and rotational motion together.

$$
\omega = \frac{d\theta}{dt},
\qquad
\alpha = \frac{d\omega}{dt}
$$

$$
\omega_f = \omega_i + \alpha t
$$

$$
\theta_f = \theta_i + \omega_i t + \frac{1}{2}\alpha t^2
$$

$$
\omega_f^2 = \omega_i^2 + 2\alpha(\theta_f - \theta_i)
$$

$$
s = r\theta,
\qquad
v = r\omega,
\qquad
a_t = r\alpha
$$

$$
K_R = \frac{1}{2}I\omega^2
$$

$$
\tau = r \times F
$$

$$
\sum \tau = I\alpha
$$

$$
v_{\text{cm}} = R\omega
$$

## Angular Momentum
- Angular momentum is conserved if the external torque is zero.

$$
L = r \times p
$$

$$
L = I\omega
$$

$$
\sum \tau = \frac{dL}{dt}
$$

## Static Equilibrium and Elasticity
- Equilibrium requires zero net force and zero net torque.
- Elastic response is described through stress, strain, and elastic moduli.

$$
\sum F = 0,
\qquad
\sum \tau = 0
$$

$$
\sigma = \frac{F}{A}
$$

$$
Y = \frac{(F/A)}{(\Delta L/L_0)}
$$

$$
S = \frac{(F/A)}{(\Delta x/h)}
$$

$$
B = -\frac{\Delta P}{(\Delta V/V_0)}
$$

## Universal Gravitation
- Newton's law of gravitation governs inverse-square attraction.
- Planetary orbits follow from gravitational dynamics and energy conservation.

$$
F = G\frac{m_1 m_2}{r^2}
$$

$$
g = \frac{GM}{r^2}
$$

$$
U = -\frac{GMm}{r}
$$

$$
v = \sqrt{\frac{GM}{r}}
$$

$$
E = -\frac{GMm}{2r}
$$

$$
v_e = \sqrt{\frac{2GM}{r}}
$$

$$
T^2 \propto r^3
$$

## Fluid Mechanics
- Pressure varies with depth in a fluid at rest.
- Buoyancy equals the weight of the displaced fluid.
- Ideal fluid flow obeys continuity and Bernoulli's equation.

$$
P = \frac{F}{A}
$$

$$
P = P_0 + \rho gh
$$

$$
B = \rho_{\text{fluid}} g V_{\text{displaced}}
$$

$$
A_1 v_1 = A_2 v_2
$$

$$
P + \frac{1}{2}\rho v^2 + \rho gy = \text{constant}
$$

# Oscillations and Mechanical Waves

## Oscillatory Motion
- Simple harmonic motion is driven by a restoring force proportional to displacement.
- Springs and pendulums are standard SHM systems.

$$
F = -kx
$$

$$
a = -\omega^2 x
$$

$$
x = A \cos(\omega t + \phi)
$$

$$
v = -A\omega \sin(\omega t + \phi)
$$

$$
\omega = \sqrt{\frac{k}{m}},
\qquad
T = 2\pi \sqrt{\frac{m}{k}}
$$

$$
\omega = \sqrt{\frac{g}{L}},
\qquad
T = 2\pi \sqrt{\frac{L}{g}}
$$

$$
E = \frac{1}{2}kA^2
$$

## Wave Motion
- Traveling waves carry energy through space.
- Wavelength, frequency, and speed are related directly.

$$
y(x,t) = A \sin(kx - \omega t + \phi)
$$

$$
v = \frac{\omega}{k} = \lambda f
$$

$$
\lambda = \frac{v}{f},
\qquad
T = \frac{1}{f}
$$

$$
v = \sqrt{\frac{T}{\mu}}
$$

## Sound Waves
- Sound is a longitudinal mechanical wave.
- Intensity and decibel level quantify loudness.

$$
I = \frac{P}{A}
$$

$$
\beta = 10 \log_{10}\left(\frac{I}{I_0}\right)
$$

## Superposition and Standing Waves
- Superposition produces interference and standing waves.
- Resonance occurs when the driving frequency matches a natural frequency.

$$
\text{constructive: } \Delta r = m\lambda
$$

$$
\text{destructive: } \Delta r = \left(m + \frac{1}{2}\right)\lambda
$$

$$
\lambda_n = \frac{2L}{n},
\qquad
f_n = \frac{nv}{2L}
$$

$$
f_{\text{beat}} = |f_1 - f_2|
$$

# Thermodynamics

## Temperature
- Temperature defines thermal equilibrium.
- Ideal gases obey a simple state equation.
- Solids and fluids expand with temperature.

$$
\Delta L = \alpha L_0 \Delta T
$$

$$
\Delta V = \beta V_0 \Delta T
$$

$$
PV = nRT = Nk_B T
$$

## Heat and the First Law of Thermodynamics
- Heat and work both transfer energy.
- The first law tracks the internal-energy change of a system.

$$
Q = mc\Delta T
$$

$$
Q = mL
$$

$$
\Delta U = Q - W
$$

$$
W = \int P \, dV
$$

$$
C_P - C_V = R
$$

## The Kinetic Theory of Gases
- Gas pressure arises from molecular collisions.
- Temperature sets average translational kinetic energy.

$$
PV = \frac{2}{3}N K_{\text{avg}}
$$

$$
K_{\text{avg}} = \frac{3}{2}k_B T
$$

$$
v_{\text{rms}} = \sqrt{\frac{3k_B T}{m}} = \sqrt{\frac{3RT}{M}}
$$

$$
PV^\gamma = \text{constant}
$$

## Heat Engines, Entropy, and the Second Law of Thermodynamics
- No cyclic engine can convert all absorbed heat into work.
- Entropy increases for irreversible processes in isolated systems.

$$
e = \frac{W}{Q_h} = 1 - \frac{Q_c}{Q_h}
$$

$$
\text{COP}_R = \frac{Q_c}{W},
\qquad
\text{COP}_{HP} = \frac{Q_h}{W}
$$

$$
e_C = 1 - \frac{T_c}{T_h}
$$

$$
\Delta S = \int \frac{dQ_{\text{rev}}}{T}
$$

$$
\Delta S \ge 0
$$

# Electricity and Magnetism

## Electric Fields
- Charges interact through Coulomb's law.
- The electric field is force per unit charge.

$$
F = k_e\frac{q_1 q_2}{r^2}
$$

$$
E = \frac{F}{q}
$$

$$
E = k_e\frac{q}{r^2}
$$

## Gauss's Law
- Electric flux measures field passing through a surface.
- Gauss's law is most useful for highly symmetric charge distributions.

$$
\Phi_E = \int E \cdot dA
$$

$$
\Phi_E = EA\cos\theta
$$

$$
\int E \cdot dA = \frac{q_{\text{enclosed}}}{\epsilon_0}
$$

## Electric Potential
- Electric potential is potential energy per unit charge.
- The electric field is the negative gradient of potential.

$$
\Delta V = \frac{\Delta U}{q}
$$

$$
W = -\Delta U = -q\Delta V
$$

$$
V = k_e\frac{q}{r}
$$

$$
E_x = -\frac{dV}{dx},
\qquad
E = -\nabla V
$$

## Capacitance and Dielectrics
- Capacitance measures charge stored per potential difference.
- Dielectrics increase capacitance.

$$
C = \frac{Q}{\Delta V}
$$

$$
C = \epsilon_0 \frac{A}{d}
$$

$$
\frac{1}{C_{\text{eq}}} = \sum \frac{1}{C_i}
$$

$$
C_{\text{eq}} = \sum C_i
$$

$$
U = \frac{1}{2}C(\Delta V)^2 = \frac{Q^2}{2C} = \frac{1}{2}Q\Delta V
$$

## Current and Resistance
- Current is the rate of charge flow.
- Resistance depends on material resistivity and geometry.

$$
I = \frac{dQ}{dt}
$$

$$
J = \frac{I}{A} = nqv_d
$$

$$
\Delta V = IR
$$

$$
R = \rho \frac{L}{A}
$$

$$
P = I\Delta V = I^2R = \frac{(\Delta V)^2}{R}
$$

## Direct Current Circuits
- Use Kirchhoff's rules for complex circuit analysis.
- RC circuits charge and discharge exponentially.

$$
R_{\text{eq, series}} = \sum R_i
$$

$$
\frac{1}{R_{\text{eq, parallel}}} = \sum \frac{1}{R_i}
$$

$$
\sum I_{\text{in}} = \sum I_{\text{out}}
$$

$$
\sum \Delta V = 0
$$

$$
q(t) = C\epsilon\left(1 - e^{-t/RC}\right)
$$

$$
I(t) = \frac{\epsilon}{R} e^{-t/RC}
$$

$$
q(t) = Q_0 e^{-t/RC}
$$

## Magnetic Fields
- Magnetic forces act on moving charges and currents.
- Magnetic forces change direction of motion but do no work.

$$
F = q\,v \times B
$$

$$
|F| = qvB\sin\theta
$$

$$
F = I\,L \times B
$$

$$
\tau = \mu \times B
$$

$$
\mu = IA\hat{n}
$$

$$
r = \frac{mv}{qB},
\qquad
\omega = \frac{qB}{m}
$$

## Sources of Magnetic Field
- Currents generate magnetic fields.
- Ampere's law and Biot-Savart are the main tools.

$$
B = \mu_0 \frac{I}{2\pi r}
$$

$$
\frac{F}{L} = \mu_0 \frac{I_1 I_2}{2\pi d}
$$

$$
\oint B \cdot dl = \mu_0 I_{\text{enclosed}}
$$

$$
B = \mu_0 n I
$$

$$
\Phi_B = \int B \cdot dA
$$

## Faraday's Law
- A changing magnetic flux induces an emf.
- Lenz's law sets the sign of the induced emf.

$$
\epsilon = -\frac{d\Phi_B}{dt}
$$

$$
\epsilon = Blv
$$

## Inductance
- Inductors resist changes in current.
- LC and RLC circuits oscillate or decay depending on resistance.

$$
\epsilon_L = -L\frac{dI}{dt}
$$

$$
U_B = \frac{1}{2}LI^2
$$

$$
I(t) = \frac{\epsilon}{R}\left(1 - e^{-t/\tau}\right),
\qquad
\tau = \frac{L}{R}
$$

$$
I(t) = I_0 e^{-t/\tau}
$$

$$
\omega = \frac{1}{\sqrt{LC}}
$$

## Alternating Current Circuits
- AC circuit behavior depends on impedance and phase.
- Resonance occurs when inductive and capacitive effects balance.

$$
\Delta v = \Delta V_{\max}\sin(\omega t)
$$

$$
V_{\text{rms}} = \frac{V_{\max}}{\sqrt{2}},
\qquad
I_{\text{rms}} = \frac{I_{\max}}{\sqrt{2}}
$$

$$
X_L = \omega L,
\qquad
X_C = \frac{1}{\omega C}
$$

$$
Z = \sqrt{R^2 + (X_L - X_C)^2}
$$

$$
P_{\text{avg}} = I_{\text{rms}}V_{\text{rms}}\cos\phi
$$

$$
\omega_0 = \frac{1}{\sqrt{LC}}
$$

$$
\frac{V_s}{V_p} = \frac{N_s}{N_p}
$$

## Electromagnetic Waves
- Maxwell's equations predict self-propagating electromagnetic waves.
- Electric and magnetic fields are perpendicular to each other and the direction of propagation.

$$
c = \frac{1}{\sqrt{\mu_0 \epsilon_0}}
$$

$$
E = cB
$$

# Light and Optics

## The Nature of Light and the Laws of Geometric Optics
- Reflection and refraction govern geometric optics.
- Total internal reflection requires incidence beyond the critical angle.

$$
\theta_i = \theta_r
$$

$$
n_1 \sin\theta_1 = n_2 \sin\theta_2
$$

$$
n = \frac{c}{v}
$$

$$
\sin\theta_c = \frac{n_2}{n_1}
$$

## Image Formation
- Mirrors and lenses obey the same thin-optics equation form.

$$
\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}
$$

$$
m = -\frac{d_i}{d_o} = \frac{h_i}{h_o}
$$

$$
P = \frac{1}{f}
$$

## Interference of Light Waves
- Interference depends on path difference and phase relation.

$$
\text{constructive: } \Delta r = m\lambda
$$

$$
\text{destructive: } \Delta r = \left(m + \frac{1}{2}\right)\lambda
$$

$$
d\sin\theta = m\lambda
$$

$$
y_m \approx \frac{m\lambda L}{d}
$$

## Diffraction Patterns and Polarization
- Diffraction sets resolution limits.
- Polarization restricts the electric-field oscillation direction.

$$
a\sin\theta = m\lambda
$$

$$
\theta_{\min} = 1.22\frac{\lambda}{D}
$$

$$
d\sin\theta = m\lambda
$$

$$
I = I_0 \cos^2\theta
$$

# Modern Physics

## Relativity
- Special relativity is built on invariant physical laws and invariant light speed.
- Time, length, momentum, and energy all change at relativistic speeds.

$$
\gamma = \frac{1}{\sqrt{1 - v^2/c^2}}
$$

$$
\Delta t = \gamma \Delta t_0
$$

$$
L = \frac{L_0}{\gamma}
$$

$$
p = \gamma mv
$$

$$
E = \gamma mc^2
$$

$$
E_0 = mc^2
$$

$$
E^2 = (pc)^2 + (mc^2)^2
$$
