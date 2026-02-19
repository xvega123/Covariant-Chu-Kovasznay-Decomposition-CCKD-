# CCKD: Covariant Chu-Kovasznay Decomposition

> **Research Overview & Supplementary Material**
> 
> *This repository serves as an archive for the Covariant Chu-Kovasznay Decomposition (CCKD), a geometric framework resolving thermodynamic ambiguity in compressible flows.*

---

## Abstract
Separating acoustic, vortical, and thermodynamic fluctuations near strong inhomogeneities (like shocks or thermal lenses) often leads to geometric leakage, where curvature-induced kinematic signatures are misidentified. 

The **CCKD** extends the kinematic CHHD framework into a complete thermodynamic decomposition formulated on the effective acoustic spacetime. By enforcing orthogonality in the covariant Chu energy norm, we establish that shock-turbulence interaction is a near-unitary scattering map constrained by Chu-energy flux conservation. This framework demonstrates that the transfer of entropy fluctuations into sound follows a geometric blue-shift, opening the door to "shock-wave holography".

**Paper Reference:**
> **C. Park**, G. Gong, Y. Kwak, and S. Choi, "Covariant Chu-Kovasznay Decomposition: Resolving Thermodynamic Ambiguity in Compressible Flows," *arXiv:2602.12093 [physics.flu-dyn]*, 2026. (Submitted to Physical Review Letters)
> **DOI:** [10.48550/arXiv.2602.12093](https://doi.org/10.48550/arXiv.2602.12093)

---

## Key Methodologies

### 1. The Covariant Chu Energy Norm
* Extends the classical acoustic energy density to inhomogeneous, shearing backgrounds in a coordinate-invariant manner.
* Guarantees energy additivity across the projected subspaces (Entropy, Acoustic, Vortical).

### 2. Three-Stage Decomposition
* **Thermodynamic Projection:** Isolates the non-propagating entropic subspace.
* **Covariant Helmholtz Decomposition:** Solves a weak covariant Poisson problem to extract the acoustic velocity.
* **Hydrodynamic Pressure Balance:** Isolates the hydrodynamic footprint (pseudo-sound) supported by mean shear from unsteady acoustic fluctuations.

---

## Key Findings

* **Unitary Shock Scattering:** Within linear inviscid theory, the cross-shock mapping is an isometric scattering operator on the covariant subspace. Incident entropic flux is converted into acoustic flux while total Chu flux is conserved.
* **Thermo-Acoustic Lens & Geometric Blue-Shift:** The shock functions as a lens, producing a deterministic geometric blue-shift ($k_{out} = \Lambda k_{in}$) that maps upstream thermodynamic structure into a high-frequency acoustic carrier.
* **Shock-Wave Holography:** The upstream state can be reconstructed from downstream acoustic observations to machine precision via an inverse-scattering law, confirming the shock as an information-preserving channel.

---

## Code Availability
The source code for the CCKD numerical operators (including mimetic finite-difference routines) is available upon request. 

Please contact the authors via email for access.

## Citation
For more details, please refer to our work:

```bibtex
@misc{park2026cckd,
      title={Covariant Chu-Kovasznay Decomposition: Resolving Thermodynamic Ambiguity in Compressible Flows}, 
      author={Chanho Park and Gyeongho Gong and Yeachan Kwak and Seongim Choi},
      year={2026},
      eprint={2602.12093},
      archivePrefix={arXiv},
      primaryClass={physics.flu-dyn},
      url={[https://doi.org/10.48550/arXiv.2602.12093](https://doi.org/10.48550/arXiv.2602.12093)}, 
      note={Submitted to Physical Review Letters}
}
