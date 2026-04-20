# Physics Cheat Sheet

# Mechanics

## Physics and Measurement
- SI base quantities: length $(m)$, mass $(kg)$, time $(s)$.
- Derived quantities: density $\rho = m / V$.
- Use dimensional analysis to check equations and derive unit consistency.
- Convert units by multiplying by dimensionless conversion factors.
- Track significant figures through calculations.
- Order-of-magnitude estimates are often enough for first-pass physics reasoning.

## Motion in One Dimension
- Displacement: $\Delta x = x_f - x_i$.
- Average velocity: $v_avg = \Delta x / \Delta t$.
- Instantaneous velocity: $v = dx/dt$.
- Average speed: total distance / total time.
- Average acceleration: $a_avg = \Delta v / \Delta t$.
- Instantaneous acceleration: $a = dv/dt = d^2x/dt^2$.
- Constant-acceleration kinematics:
  - $v_f = v_i + at$
  - $x_f = x_i + v_i t + (1/2)at^2$
  - $v_f^2 = v_i^2 + 2a(x_f - x_i)$
  - $x_f - x_i = (1/2)(v_i + v_f)t$
- Free fall: $a = -g$ if up is positive.

## Vectors
- Scalars have magnitude only; vectors have magnitude and direction.
- Vector magnitude in components: $|A| = \sqrt{A_x^2 + A_y^2}$.
- Unit vector: $\hat{u} = A / |A|$.
- Component form: $A = A_x \hat{i} + A_y \hat{j} (+ A_z \hat{k})$.
- Add vectors by components.
- Dot product: $A \cdot B = AB \cos(\theta) = A_x B_x + A_y B_y + A_z B_z$.

## Motion in Two Dimensions
- Position, velocity, and acceleration are vector quantities.
- Treat x- and y-motion independently.
- Projectile motion:
  - $x = v_0 \cos(\theta) t$
  - $y = v_0 \sin(\theta) t - (1/2)gt^2$
  - $v_x = v_0 \cos(\theta)$, $v_y = v_0 \sin(\theta) - gt$
- Uniform circular motion:
  - centripetal acceleration $a_r = v^2 / r = \omega^2 r$
  - tangential acceleration $a_t = dv/dt$
- Relative velocity: $v_A/C = v_A/B + v_B/C$.

## The Laws of Motion
- Newton's First Law: constant velocity when net force is zero.
- Newton's Second Law: $\sum F = ma$.
- Newton's Third Law: interaction forces are equal in magnitude and opposite in direction.
- Weight: $W = mg$.
- Friction:
  - static $f_s \le \mu_s N$
  - kinetic $f_k = \mu_k N$
- Draw a free-body diagram before writing equations.

## Circular Motion and Other Applications of Newton's Laws
- Radial force requirement for circular motion: $\sum F_r = mv^2 / r$.
- Nonuniform circular motion can include both radial and tangential acceleration.
- Banked curve without friction: $\tan(\theta) = v^2 / (rg)$.
- Apparent forces arise in accelerating frames.
- Resistive-force models often use $f = -bv$ or $f = -cv^2$.

## Energy and Energy Transfer
- Work by a constant force: $W = F d \cos(\theta)$.
- Work by a variable force: $W = \int F_x dx$.
- Kinetic energy: $K = (1/2)mv^2$.
- Work-kinetic energy theorem: $W_net = \Delta K$.
- Power:
  - average $P_avg = \Delta W / \Delta t$
  - instantaneous $P = dW/dt = F \cdot v$
- In a nonisolated system: $\Delta E_system = T + W + Q$, depending on the transfer model used.

## Potential Energy
- Conservative force has associated potential energy $U$.
- Gravitational potential near Earth: $U_g = mgy$.
- Spring potential: $U_s = (1/2)kx^2$.
- Conservation of mechanical energy for an isolated system:
  - $K_i + U_i = K_f + U_f$
- For conservative forces: $F_x = -dU/dx$.
- Stable equilibrium occurs near a minimum of $U(x)$.

## Linear Momentum and Collisions
- Linear momentum: $p = mv$.
- Impulse: $J = \int F dt = \Delta p$.
- Momentum conservation for an isolated system: $\sum p_i = \sum p_f$.
- Perfectly inelastic collision: objects stick together; momentum conserved, kinetic energy not conserved.
- Elastic collision: both momentum and kinetic energy conserved.
- Center of mass:
  - $r_{\rm cm} = (\sum m_i r_i) / (\sum m_i)$
  - $v_{\rm cm} = (\sum m_i v_i) / (\sum m_i)$
- Rocket equation: $\Delta v = v_e \ln(m_i / m_f)$.

## Rotation of a Rigid Object about a Fixed Axis
- Angular kinematics:
  - $\omega = d\theta/dt$
  - $\alpha = d\omega/dt$
- Constant-angular-acceleration relations:
  - $\omega_f = \omega_i + \alpha t$
  - $\theta_f = \theta_i + \omega_i t + (1/2)\alpha t^2$
  - $\omega_f^2 = \omega_i^2 + 2\alpha(\theta_f - \theta_i)$
- Linear and angular links:
  - $s = r \theta$
  - $v = r \omega$
  - $a_t = r \alpha$
- Rotational kinetic energy: $K_R = (1/2)I \omega^2$.
- Torque: $\tau = r \times F$, magnitude $\tau = Fd$.
- Rotational dynamics: $\sum \tau = I \alpha$.
- Rolling without slipping: $v_{\rm cm} = R \omega$.

## Angular Momentum
- Particle angular momentum: $L = r \times p$.
- Rigid body about fixed axis: $L = I \omega$.
- Rotational form of Newton's second law: $\sum \tau = dL/dt$.
- If external torque is zero, angular momentum is conserved.
- This conservation explains spin-up and spin-down in rotating systems.

## Static Equilibrium and Elasticity
- Translational equilibrium: $\sum F = 0$.
- Rotational equilibrium: $\sum \tau = 0$.
- Center of gravity is the point where the weight can be treated as acting.
- Stress: $\sigma = F / A$.
- Strain:
  - tensile/compressive $\Delta L / L_0$
  - shear $\Delta x / h$
- Young's modulus: $Y = (F/A) / (\Delta L/L_0)$.
- Shear modulus: $S = (F/A) / (\Delta x/h)$.
- Bulk modulus: $B = -\Delta P / (\Delta V/V_0)$.

## Universal Gravitation
- Newton's law of gravitation: $F = G m_1 m_2 / r^2$.
- Gravitational field: $g = F/m = GM/r^2$.
- Gravitational potential energy: $U = -G M m / r$.
- Circular-orbit speed: $v = \sqrt{GM/r}$.
- Total energy in circular orbit: $E = -GMm/(2r)$.
- Escape speed: $v_e = \sqrt{2GM/r}$.
- Kepler's third law for planets: $T^2 \propto r^3$.

## Fluid Mechanics
- Pressure: $P = F / A$.
- Hydrostatic pressure: $P = P_0 + \rho g h$.
- Buoyant force: $B = \rho_{\text{fluid}} g V_displaced$.
- Continuity equation for ideal fluids: $A_1 v_1 = A_2 v_2$.
- Bernoulli's equation:
  - $P + (1/2)\rho v^2 + \rho g y = constant$
- Faster fluid flow corresponds to lower pressure in Bernoulli-type situations.

# Oscillations and Mechanical Waves

## Oscillatory Motion
- Hooke's law: $F = -kx$.
- Simple harmonic motion obeys $a = -\omega^2 x$.
- Position, velocity, acceleration:
  - $x = A \cos(\omega t + \phi)$
  - $v = -A \omega \sin(\omega t + \phi)$
  - $a = -\omega^2 x$
- Spring-mass oscillator: $\omega = \sqrt{k/m}$, $T = 2\pi \sqrt{m/k}$.
- Pendulum for small angles: $\omega = \sqrt{g/L}$, $T = 2\pi \sqrt{L/g}$.
- Total energy in SHM: $E = (1/2)kA^2$.
- Damping removes energy; driving can produce resonance.

## Wave Motion
- Traveling sinusoidal wave:
  - $y(x,t) = A \sin(kx - \omega t + \phi)$
- Wave speed: $v = \omega / k = \lambda f$.
- Wavelength and frequency: $\lambda = v/f$, $T = 1/f$.
- Wave on a string: $v = \sqrt{T/\mu}$, where $\mu$ is linear mass density.
- Linear wave equation describes ideal wave propagation.
- Reflection and transmission depend on boundary conditions and medium properties.

## Sound Waves
- Sound is a longitudinal mechanical wave.
- Speed of sound depends on medium properties.
- Intensity: $I = P/A$.
- Decibel level: $\beta = 10 \log_{10}(I/I_0)$.
- Doppler effect for sound shifts observed frequency with source/observer motion.
- Standing sound waves in air columns produce resonant frequencies.

## Superposition and Standing Waves
- Principle of superposition: displacements add algebraically.
- Interference:
  - constructive when path difference is $m \lambda$
  - destructive when path difference is $(m + 1/2)\lambda$
- Standing waves on a string fixed at both ends:
  - $\lambda_n = 2L/n$
  - $f_n = n v / (2L)$
- Beats: $f_beat = |f_1 - f_2|$.
- Resonance occurs when driving frequency matches a natural frequency.

# Thermodynamics

## Temperature
- Zeroth law: if A is in thermal equilibrium with B, and B with C, then A with C.
- Absolute temperature is measured in kelvins.
- Linear expansion: $\Delta L = \alpha L_0 \Delta T$.
- Volume expansion: $\Delta V = \beta V_0 \Delta T$.
- Ideal-gas law: $PV = nRT = N k_B T$.

## Heat and the First Law of Thermodynamics
- Internal energy changes by heat and work.
- Heat transfer:
  - $Q = mc \Delta T$
  - phase change $Q = mL$
- First law of thermodynamics: $\Delta U = Q - W$.
- Work done by a gas: $W = \int P dV$.
- Molar specific heats for ideal gases:
  - $C_P - C_V = R$
- Special processes:
  - isobaric $W = P \Delta V$
  - isochoric $W = 0$
  - isothermal for ideal gas $\Delta U = 0$
  - adiabatic $Q = 0$

## The Kinetic Theory of Gases
- Ideal-gas pressure from molecular motion: $PV = (2/3)N K_avg$.
- Average translational kinetic energy per molecule:
  - $K_avg = (3/2)k_B T$
- RMS speed: $v_rms = \sqrt{3k_B T / m} = \sqrt{3RT/M}$.
- Equipartition: each quadratic degree of freedom contributes $(1/2)k_B T$ per molecule.
- Adiabatic ideal-gas process: $PV^\gamma = constant$.
- Mean free path characterizes average collision spacing.

## Heat Engines, Entropy, and the Second Law of Thermodynamics
- Heat engine efficiency: $e = W/Q_h = 1 - Q_c/Q_h$.
- Refrigerator coefficient of performance: $COP_R = Q_c/W$.
- Heat pump coefficient of performance: $COP_HP = Q_h/W$.
- Second law: no cyclic device can convert all absorbed heat into work.
- Carnot efficiency: $e_C = 1 - T_c/T_h$.
- Entropy change for reversible heat transfer: $\Delta S = \int dQ_rev / T$.
- For an isolated system, $\Delta S \ge 0$.

# Electricity and Magnetism

## Electric Fields
- Coulomb's law: $F = k_e q_1 q_2 / r^2$.
- Electric field: $E = F/q$.
- Point-charge field: $E = k_e q / r^2$, radial in direction.
- Continuous distributions require integration.
- Electric field lines point in the direction of the force on a positive test charge.
- In a uniform electric field, $F = qE$ and $a = qE/m$.

## Gauss's Law
- Electric flux: $\Phi_E = \int E \cdot dA$.
- For a uniform field on a flat area: $\Phi_E = EA \cos(\theta)$.
- Gauss's law:
  - $\int E \cdot dA = q_{\rm enclosed} / \epsilon_0$
- Best used with high symmetry: spherical, cylindrical, planar.
- In electrostatic equilibrium, electric field inside a conductor is zero.

## Electric Potential
- Potential difference: $\Delta V = \Delta U / q$.
- Work by electric field: $W = -\Delta U = -q \Delta V$.
- Uniform field: $\Delta V = -E d$ along the field direction.
- Point-charge potential: $V = k_e q / r$.
- Superposition applies to electric potential.
- Electric field from potential:
  - $E_x = -dV/dx$
  - vector form $E = -\nabla V$

## Capacitance and Dielectrics
- Capacitance: $C = Q / \Delta V$.
- Parallel-plate capacitor: $C = \epsilon_0 A / d$.
- Series capacitors: $1/C_{\rm eq} = \sum (1/C_i)$.
- Parallel capacitors: $C_{\rm eq} = \sum C_i$.
- Energy stored:
  - $U = (1/2)C(\Delta V)^2 = Q^2/(2C) = (1/2)Q \Delta V$
- Dielectric increases capacitance by factor $\kappa$: $C = \kappa C_0$.

## Current and Resistance
- Electric current: $I = dQ/dt$.
- Current density: $J = I/A = nqv_d$.
- Ohm's law for ohmic materials: $\Delta V = IR$.
- Resistance of a uniform conductor: $R = \rho L / A$.
- Electrical power:
  - $P = I \Delta V = I^2 R = (\Delta V)^2 / R$
- Resistivity typically rises with temperature in metals.

## Direct Current Circuits
- emf is energy supplied per unit charge.
- Resistors:
  - series $R_{\rm eq} = \sum R_i$
  - parallel $1/R_{\rm eq} = \sum (1/R_i)$
- Kirchhoff's junction rule: $\sum I_in = \sum I_out$.
- Kirchhoff's loop rule: $\sum \Delta V = 0$.
- RC charging:
  - $q(t) = C \epsilon (1 - e^(-t/RC))$
  - $I(t) = (\epsilon/R)e^(-t/RC)$
- RC discharging:
  - $q(t) = Q_0 e^(-t/RC)$
  - $I(t) = -(Q_0/RC)e^(-t/RC)$

## Magnetic Fields
- Magnetic force on moving charge: $F = q v \times B$, magnitude $F = qvB \sin(\theta)$.
- Force on current-carrying wire: $F = I L \times B$.
- Torque on current loop: $\tau = \mu \times B$.
- Magnetic dipole moment: $\mu = I A \hat{n}$.
- Circular motion in uniform magnetic field:
  - $r = mv/(qB)$
  - $\omega = qB/m$
- Magnetic force does no work on a charged particle.

## Sources of Magnetic Field
- Biot-Savart law gives $dB$ from current element $I d l$.
- Field near a long straight wire: $B = \mu_0 I / (2\pi r)$.
- Force per unit length between parallel currents:
  - $F/L = \mu_0 I_1 I_2 / (2\pi d)$
- Ampere's law: $\oint B \cdot dl = \mu_0 I_enclosed$.
- Solenoid field: $B = \mu_0 n I$ for an ideal long solenoid.
- Magnetic flux: $\Phi_B = \int B \cdot dA$.
- Gauss's law for magnetism: net magnetic flux through a closed surface is zero.

## Faraday's Law
- Induced emf:
  - $\epsilon = -d\Phi_B/dt$
- Lenz's law gives the sign: induced current opposes the flux change.
- Motional emf: $\epsilon = B l v$ for a rod moving perpendicularly through a field.
- Changing magnetic fields produce electric fields.
- Maxwell's equations unify electricity and magnetism.

## Inductance
- Self-induced emf: $\epsilon_L = -L dI/dt$.
- Inductor energy: $U_B = (1/2)LI^2$.
- RL current growth:
  - $I(t) = (\epsilon/R)(1 - e^(-t/\tau))$, $\tau = L/R$
- RL decay:
  - $I(t) = I_0 e^(-t/\tau)$
- LC oscillator angular frequency: $\omega = 1/\sqrt{LC}$.
- RLC circuits combine resistance, capacitance, and inductance into damped oscillation.

## Alternating Current Circuits
- AC source: $\Delta v = \Delta V_{\max} \sin(\omega t)$.
- RMS values:
  - $V_{\rm rms} = V_{\max} / \sqrt{2}$
  - $I_{\rm rms} = I_{\max} / \sqrt{2}$
- Reactances:
  - inductive $X_L = \omega L$
  - capacitive $X_C = 1/(\omega C)$
- Impedance in series RLC:
  - $Z = \sqrt{R^2 + (X_L - X_C)^2}$
- Average power: $P_{\rm avg} = I_{\rm rms} V_{\rm rms} \cos(\phi)$.
- Resonance at $\omega_0 = 1/\sqrt{LC}$.
- Transformers: $V_s/V_p = N_s/N_p$.

## Electromagnetic Waves
- Maxwell's equations predict self-propagating EM waves.
- Wave speed in vacuum: $c = 1/\sqrt{\mu_0 \epsilon_0}$.
- In an EM wave, $E$ and $B$ are perpendicular to each other and to propagation.
- Magnitude relation: $E = cB$.
- Energy flow is described by the Poynting vector.
- Radiation pressure follows from EM wave momentum transport.

# Light and Optics

## The Nature of Light and the Laws of Geometric Optics
- Reflection: $\theta_i = \theta_r$.
- Refraction (Snell's law): $n_1 \sin(\theta_1) = n_2 \sin(\theta_2)$.
- Refractive index: $n = c/v$.
- Total internal reflection occurs when light goes from higher to lower $n$ and $\theta_i > \theta_c$.
- Critical angle: $\sin(\theta_c) = n_2/n_1$, for $n_1 > n_2$.
- Dispersion occurs because $n$ depends on wavelength.

## Image Formation
- Plane mirror: $d_i = -d_o$, magnification $m = 1$.
- Spherical mirror equation: $1/f = 1/d_o + 1/d_i$.
- Mirror magnification: $m = -d_i/d_o = h_i/h_o$.
- Thin-lens equation: $1/f = 1/d_o + 1/d_i$.
- Lens power: $P = 1/f$ in diopters when $f$ is in meters.
- Image sign conventions determine real/virtual and upright/inverted images.

## Interference of Light Waves
- Constructive interference: path difference $\Delta r = m \lambda$.
- Destructive interference: $\Delta r = (m + 1/2)\lambda$.
- Double-slit bright fringes:
  - $d \sin(\theta) = m \lambda$
- For small angles on a screen: $y_m \approx m \lambda L / d$.
- Thin-film interference depends on path difference and phase shifts on reflection.

## Diffraction Patterns and Polarization
- Single-slit minima: $a \sin(\theta) = m \lambda$, $m = 1, 2, 3, ...$
- Circular-aperture Rayleigh criterion: $\theta_min = 1.22 \lambda / D$.
- Diffraction grating maxima: $d \sin(\theta) = m \lambda$.
- Polarized light has electric field oscillation confined to a direction.
- Malus's law: $I = I_0 \cos^2(\theta)$.

# Modern Physics

## Relativity
- Postulates of special relativity:
  - laws of physics are the same in all inertial frames
  - speed of light is the same for all inertial observers
- Time dilation: $\Delta t = \gamma \Delta t_0$.
- Length contraction: $L = L_0/\gamma$.
- Relativistic factor: $\gamma = 1/\sqrt{1 - v^2/c^2}$.
- Relativistic momentum: $p = \gamma m v$.
- Total energy: $E = \gamma m c^2$.
- Rest energy: $E_0 = mc^2$.
- Energy-momentum relation: $E^2 = (pc)^2 + (mc^2)^2$.
