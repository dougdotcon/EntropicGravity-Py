# Information as Geometry: A Computational Verification of Entropic Gravity from Galactic Scales to Cosmic Expansion

**Author:** Douglas 
**Affiliation:** Institute for Advanced Research in Complex Systems  
**Date:** December 2025

---

## Abstract

We present a comprehensive computational audit of Emergent Gravity, specifically testing the hypothesis that Dark Matter is an illusory effect arising from the entropy of spacetime information. By implementing a suite of numerical simulations ranging from galactic dynamics to cosmological expansion, we demonstrate that a purely baryonic universe, when corrected for entropic forces, reproduces key observational phenomena attributed to Dark Matter. Our results confirm flat rotation curves, stable galactic disks, and gravitational lensing profiles consistent with isothermal halos. Furthermore, we address the cosmological expansion history, proposing a "Reactive Dark Matter" model where the apparent mass scales with the Hubble parameter ($H(z)$), partially resolving the tension with standard $\Lambda$CDM.

---

## 1. Introduction: The Dark Matter Crisis

The Standard Model of Cosmology ($\Lambda$CDM) relies on the existence of Cold Dark Matter (CDM) to explain the rotation speeds of galaxies and the structure of the universe. However, despite decades of searching, no particle candidate (WIMP, Axion) has been detected.

**Entropic Gravity**, proposed by Erik Verlinde (2011, 2016), offers a radical alternative: Gravity is not a fundamental force, but an emergent thermodynamic phenomenon. In this view, "Dark Matter" is the result of the elastic response of spacetime entropy to the presence of baryonic matter, becoming relevant only at low acceleration scales ($a < a_0$).

This paper details a **"Code-First Physics"** approach to validating this theory, prioritizing numerical simulation over analytical approximation.

---

## 2. Theoretical Framework

The core equation governing the effective gravitational acceleration $g$ in the Entropic framework is the interpolation between Newtonian ($g_N$) and Deep MOND ($g_M$) regimes:

$$ g = \frac{g_N + \sqrt{g_N^2 + 4 g_N a_0}}{2} $$

Where:
*   $g_N = G M / r^2$ is the standard Newtonian acceleration.
*   $a_0 \approx 1.2 \times 10^{-10} m/s^2$ is the acceleration scale related to the Hubble constant ($a_0 \approx cH_0$).

At large distances ($g_N \ll a_0$), the force decays as $1/r$ rather than $1/r^2$, naturally producing flat rotation curves ($v \approx constant$).

---

## 3. Methodology: The Validation Suite

To ensure scientific rigor, we subjected the theory to 7 distinct computational challenges:

1.  **Energy Conservation:** Verifying Hamiltonian stability.
2.  **Derivation:** Implementing smooth interpolations.
3.  **Boundary Conditions:** Testing the Strong Equivalence Principle (SEP) and External Field Effect (EFE).
4.  **Disk Stability:** Calculating the Toomre $Q$ parameter.
5.  **Convergence:** Richardson Extrapolation for numerical accuracy.
6.  **Gravitational Lensing:** Ray-tracing simulation.
7.  **Cosmology:** Solving the Friedmann Equation with entropic corrections.

---

## 4. Results

### 4.1 Galactic Dynamics
Our N-Body simulations confirm that the entropic correction naturally flattens rotation curves without requiring invisible mass.
*   **Key Finding:** The transition from Newtonian to Entropic behavior occurs exactly at the acceleration scale $a_0$, matching observations (Tully-Fisher relation).

### 4.2 Disk Stability (Toomre Q)
A major criticism of non-DM theories is that galactic disks would fly apart. Our stability analysis proved otherwise.
*   **Result:** The entropic force creates a "Phantom Halo" effect, increasing the epicyclic frequency $\kappa$.
*   **Outcome:** The disk remains stable ($Q > 1$) against bar formation.

![Stability Analysis](Entropic_Gravity/Validation/stability_analysis.png)

### 4.3 Gravitational Lensing
We simulated the deflection of light by projecting the baryonic mass into a 2D density field and calculating the entropic potential.
*   **Result:** The Entropic Potential produces a deflection angle that does *not* decay to zero at large radii, mimicking the presence of a massive Dark Matter halo.
*   **Conclusion:** Geometric Equivalence is proven.

![Lensing Analysis](Entropic_Gravity/Validation/06_Gravitational_Lensing/lensing_analysis.png)

---

## 5. The Cosmological Pivot: Reactive Dark Matter

The most challenging test was reproducing the expansion history of the universe $H(z)$. A naive model using only Baryons ($\Omega_b$) failed to match the standard $\Lambda$CDM expansion.

**The Solution:** We implemented a **Reactive Emergent Gravity** model, based on the hypothesis that the apparent dark matter density is not conserved but interacts with the Hubble horizon:

$$ \Omega_{app} \propto \sqrt{H(z)} $$

This "Reactive" model significantly reduced the discrepancy with observational data, suggesting that "Dark Matter" is a memory effect of the spacetime expansion itself.

![Reactive Cosmology](Entropic_Gravity/Validation/07_Cosmology/cosmology_reactive_result.png)

---

## 6. Conclusion

We have computationally verified that **Entropic Gravity** is a viable alternative to the Dark Matter paradigm. It successfully explains:
1.  Galactic Rotation Curves (Dynamic)
2.  Disk Stability (Mechanic)
3.  Gravitational Lensing (Geometric)

While the Cosmological expansion requires further refinement of the coupling constants, the "Reactive" framework offers a promising path forward. We conclude that **Information is Geometry**, and the "dark sector" is merely the thermodynamic signature of empty space.

---

## References
1.  Verlinde, E. (2011). *On the Origin of Gravity and the Laws of Newton*. JHEP.
2.  Verlinde, E. (2016). *Emergent Gravity and the Dark Universe*. SciPost Phys.
3.  Bekenstein, J. D. (1973). *Black holes and entropy*. Phys. Rev. D.
