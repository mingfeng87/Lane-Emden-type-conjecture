# Lane–Emden-Type Conjecture

## Project Overview

This repository contains candidate proofs of Liouville-type theorems for weighted fractional and weighted polyharmonic Lane–Emden systems. The proofs were obtained by our team on **October 08, 2026**, through extensive dialogue-based training with AI. The team is currently working to verify all the proofs.

The Lane–Emden conjecture is a well-known open problem in the theory of nonlinear elliptic partial differential equations, asserting the nonexistence of non-trivial, non-negative entire solutions to the Lane–Emden system under a critical Sobolev hyperbola condition. This repository documents our progress toward proving Liouville results in this direction.

> **Status:** Draft. These are candidate proofs, not yet fully verified.

## Main Results

### 1. Weighted Fractional Lane–Emden Systems

We consider the weighted fractional system

$$
(-\Delta)^s u = |x|^A v^p, \qquad (-\Delta)^s v = |x|^B u^q \quad \text{in } \mathbb{R}^N \setminus \{0\},
$$

where $0 < s < 1$, $N > 2s$, and the weights $A, B$ are arbitrary real numbers. We extend the localized kernel virial and interval pressure method to this setting for general solution pairs. The statement allows all real weights and all positive powers, in every integer dimension $N > 2s$.

**Key features:**

- Continuity at the origin and the usual fractional tail class are explicit.
- The potential reduction forces admissible origin weights.
- The product range $pq \le 1$ is excluded directly.
- For $pq > 1$, the weighted critical hyperbola enters through universal local energy and dilation.
- Diagonal cancellation covers $2s \le 1$; the one-dimensional pressure argument uses a single line.

### 2. Weighted Polyharmonic Lane–Emden Systems

We prove subcritical Liouville theorems for the weighted polyharmonic system

$$
(-\Delta)^m u = |x|^A v^p, \qquad (-\Delta)^m v = |x|^B u^q \quad \text{in } \mathbb{R}^N \setminus \{0\},
$$

where $m, N$ are positive integers with $N > 2m$, $p, q \ge 1$, and $pq > 1$. The weights $A, B \in \mathbb{R}$ are arbitrary. Under the subcritical condition

$$
\frac{N+A}{p+1} + \frac{N+B}{q+1} > N - 2m,
$$

we prove that there is no nonzero nonnegative solution continuous on $\mathbb{R}^N$ and classical away from the origin.

**Key features:**

- No boundedness, decay, radial symmetry, finite energy, or sign conditions on intermediate Laplacians are assumed.
- An exact Riesz representation is obtained, showing that a hypothetical nonzero solution forces $A, B > -2m$.
- A weighted virial identity and interval comparison give a universal local energy bound; subcritical scaling contradicts this bound.
- The unweighted higher-order Lane–Emden theorem follows as a corollary.

## Proof Approach

Both proofs adapt the **localized source-layer pressure method** originally developed for second-order systems. The main ingredients are:

1. **Exact potential representation** – Reduction of the differential system to Riesz potentials.
2. **Localized weighted virial identity** – Capturing the energy contribution at each scale.
3. **Interval comparison** – Deriving a universal bound on the local energy.
4. **Scaling contradiction** – Showing that subcritical scaling violates the energy bound.

For the fractional case, the fractional cancellation developed in earlier work is used, and the one-dimensional pressure argument is handled separately. For the polyharmonic case, the method is adapted to homogeneous Riesz kernels.

## Repository Contents

| File | Description |
|------|-------------|
| [`weighted-fractional-lane-emden.pdf`](https://github.com/mingfeng87/Lane-Emden-type-conjecture/blob/main/weighted-fractional-lane-emden.pdf) | Candidate proof of Liouville results for weighted fractional Lane–Emden systems with arbitrary real weights and all positive powers. |
| [`weighted-polyharmonic-lane-emden.pdf`](https://github.com/mingfeng87/Lane-Emden-type-conjecture/blob/main/weighted-polyharmonic-lane-emden.pdf) | Candidate proof of subcritical Liouville theorems for weighted polyharmonic Lane–Emden systems with arbitrary real weights. |

## Verification Status

Both documents are marked as **drafts**. The proofs were generated with AI assistance and are currently under verification by our team. We welcome independent scrutiny and feedback from the mathematical community.

## License

This project is provided for academic and research purposes. Please contact the repository owner for licensing details.

## Contact

For questions or collaboration inquiries, please open an issue on GitHub.
