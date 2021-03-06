# Introduction
This project provides codes for paper [VARIATIONAL-ASYMPTOTIC-PRESERVING-SCHEME-FORVLASOV-POISSON-FOKKER-PLANCK-SYSTEM](https://arxiv.org/abs/2007.01969). Include 1D,2D,3D spatially homogeneous case(both fix step size approach and line search approach) and 1D spatailly inhomogeneous case. For collision term, JKO scheme is considered, and MUSCL is applied to the advection term. Line search technique is used in solving JKO scheme and superlinear convergence rate is observed(by output t_k and will see t_k=1 gradually). 
# Usage of code
## Robustness to \tau, \varepsilon and N_v
```
robust_tau, robust_epsi, robust_Nv
```
```
robust_search_tau, robust_search_epsi, robust_search_Nv
```
## Robustness at different time step
```
diff_outer_step_evo, diff_outer_step_search_evo
```
## AP check 
```
AP_check
```
## Mix regime and VFP evolution
```
PN_VPFP_1D_mix_muscl, PN_search_VPFP_1D
```
## High dimension sptially homogeneous evolution
```
PN_2D_search_evo, PN_3D_search_evo
```


