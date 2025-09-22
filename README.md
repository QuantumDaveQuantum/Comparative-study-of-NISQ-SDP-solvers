NISQ_SDP

Codes for comparing different NISQ SDP solvers

Specifically, we compare the NISQ SDP solvers in [1] and [2] for the following problems:

Portfolio optimisation - turns out to write as a SDP is very inefficient
Closest covariance matrix problem. This is a weakly constrained problem so naturally suited for Ref [1]. We consider several different methods of decomposing the covariance matrix
MaxCut
An optimised SDP (optimised in the sense of making the quantum solvers look good)
[1] Bharti, Kishor, et al. "Noisy intermediate-scale quantum algorithm for semidefinite programming." Physical Review A 105.5 (2022): 052445. [2] Patel, Dhrumil, Patrick J. Coles, and Mark M. Wilde. "Variational quantum algorithms for semidefinite programming." Quantum 8 (2024): 1374.
