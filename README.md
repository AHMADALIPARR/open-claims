# Open Claims

Version 1.0.0. Public statement of the DMZ/F2 program. This repository does not prove the Riemann hypothesis. It records the claims that are open, the ingredients that are already theorems, and the file that compiled.

The compiled Lean source remains https://github.com/SNAPKITTYWEST/dmz-f2-decomposition at commit d36737c4d2241682eb16945b4bf7e41ff384a615. The Lean file is blob 7360e34bdd1af0ca98280e2d88b1f4b98fb314b9, 11958 bytes, toolchain leanprover/lean4:v4.34.0-rc1. This project does not replace that blob.

Authors of the underlying program: Ahmad Ali Parr and Jessica Westerhoff. Lab: SnapKitty Research Lab. This v1.0 text is a description of claims, not a new proof.

## Open

- O1. Non-trivial zeros of zeta(s) have real part 1/2. Open since 1859.
- O2. Hilbert-Polya: a self-adjoint H whose eigenvalues are the ordinates. Not constructed.
- B1. A zero-preserving map from F2 DMZ data to zeta zeros. Open.
- B2. A Red2 functor that preserves L-factors and the critical line, with zeta in the image. Open.
- B3. Wild ramification at p = 2. Open.
- B4. The compiled WeilBound formula is a Jacobian point count. Open. The compiled theorem is arithmetic; genus 1 is the value native_decide accepted, stated as 7.
- B5. The identity Frobenius on Mumford pairs is geometric Frobenius. Open.

## Closed by citation or compilation

Weil 1948 and Deligne 1974/1980 are the Riemann hypothesis for varieties over finite fields, not for zeta(s). Eichler-Zagier and Dabholkar-Murthy-Zagier are theorems about Jacobi forms. The compiled model is the blob above. Its Frobenius is the identity, proved by rfl. Cartier-Manin uses ZMod.sq_eq_self. WeilBound existence is the formula equal to itself.

A rewrite that changes the Finset import, drops ZMod.sq_eq_self, or uses the path Proofs.HOLLight does not compile against that pin. The directory is proofs/HOLLight.

## Release

Tag name requested: v1.0.0. Topics requested: riemann-hypothesis, open-problem, number-theory, lean, formal-methods, dmz, finite-fields. Citation metadata is in CITATION.cff and codemeta.json. The connected GitHub tools can create the repository and push files. They cannot create a release or set topics. Those two steps are listed in RELEASE_v1.0.md for the tag cut.

The full program note is 2941 words in the release working copy. This file is the public abstract. claims/OPEN.md is the register.
