# Gaussian-Beam-Propagation-in-2D-using-MATLAB
  This MATLAB script simulates and visualizes the intensity distribution of a Gaussian beam as it propagates through space. The simulation is based on scalar diffraction theory and includes the effects of beam divergence, wavefront curvature, and the Gouy phase shift.

**Equation :**
1. w(z) = w₀√(1 + (z/zR)²) --> Beam radius at position z
2. R(z) = z[1 + (zR/z)²] --> Radius of curvature of the beam's wavefront
3. ξ(z) = arctan(z/zR) --> Gouy phase shift
4. zR (Rayleigh range) : distance where beam radius √2 × w₀
5. k (wave number) = 2π/λ	
  

**Key Concepts Modeled**
1. Gaussian beam waist (w0)
2. Rayleigh range (zR)
3. Beam divergence and spreading
4. Wavefront curvature (R(z))
5. Gouy phase (ξ(z))
6. 2D electric field representation
7. Intensity profile visualization (|E|²)

**Features**
Customizable parameters: wavelength λ, beam waist w₀
Computes:
1. Beam radius w(z)
2. Curvature radius R(z)
3. Gouy phase ξ(z)

**2D visualization of intensity with overlay of beam envelope**

The output is a 2D intensity plot (|E|^2) of the beam showing the Gaussian distribution and how it spreads with propagation. The beam envelope is overlaid for reference using dashed white lines.
