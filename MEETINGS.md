# Meetings

## 07.11.23 (Initial Meeting)
Fumihiko will give me a paper
Preliminaries should already be there
Stop with current paper (Mean curvature flow) (maybe later relevant)
Start easier paper (Nonlocal Minimal Surface)

### Idea
Extention of Perimeter => Fractional Perimeter kindof gives the "Area of the boundary times
some potential factor"

Fractional Perimeter is also called nonlocal perimeter, because we need to consider not
just the elements at the boundary, but also those around it (not locally anymore)

We consider problems of the type $ min P_s (E; \Omega) $ over those sets $ E $ which have
fixed boundary $ E \setminus \Omega = E_0 $ outside of $ \Omega $.
We are interested in the local perimeter problem $ min P (E; \Omega) $, but first consider
the nonlocal perimeter problem. 
Existence and Regularity proved by Caffarelli, Roquejofre and Savin in the paper (Nonlocal
Minimal Surfaces), but we don't know how those minimizer look like yet.

Expected Behavior of minimizer, see in Paper Dipierro-Savin-Valtinoci (16,17).
Interesting behavior when considering $ \Omega $ a cylinder and $ E_0 $ the halfspace.

Look up Catenoid but these only apply in $ \mathbb{R}^3 $.
See paper Dipierro-Onoue-Valtinoci.

One possible direction of my thesis:
First think about problemsetting and then Minimizer shapes.

Maybe not consider whole halfplanes, but two cylinders with radius $ R $ and let $ R $ go
to $ \infty $ (current research of Onoue).
Behavior of the minimizer as $ R $ go to $ \infty $.

Template of Thesis from TUM.



## 21.11.23 (Second Meeting)


### Questions

1. Q.02: Why choose for $ \Omega_{k+1} = \{ u(x,\varepsilon) > \alpha \} $, $ \alpha = 0 $
   (which increases $ \Omega_{k+1} $) and not $ \alpha = 1/2 $ which correspondences to
   motion by mean curvature, cf. Merriman etal 1992.

   Answer: Probably because the initial data is $ u_k = ind_\Omega - ind_{C\Omega} $

2. Q.03: How does BM differ from Levy process, s.t. long-range correlation is considered
   in the later but not in the former? BM is as-cts, which LEvy-Proceses are not in
   general

   Answer: The usual Laplacian $ \Delta u $ is locally, but the fractional Laplacian $
   (-\Delta) ^{\frac{s}{2}} u(x) := p.v. \int_{\mathbb{R}^n}
   \frac{u(x)-u(y)}{\abs{x-y}^{d+s}} 
   Ask Marco some more on MBO-Scheme 

3. Q.07: Why are we looking at local minimizer again? We want nonlocal minimizers?

   Answer: Local in this case doesn't mean "local minimizer", but we restrict our setting
   to a bounded set $ \Omega $ s.t. everything is still in $ \Omega $. 
   "Nonlocal Minimizer" means behavior of Boundary considering the whole boundary. 
   I confused $ E_0 $ with $ \Omega $.

4. Q.08: Minimizer in what sense? If $ E_n \setminus B_1 = E_0 $, then $ (E_n \triangle
   E) \setminus B_1 = \emptyset $ (Don't understand rest of proof Thm 3.3)

   Answer: The set $ E_0 $ depends on $ n $. The minimality doesn't specify the set
   outside of $ \Omega $ or $ B_1 $ in our case.

5. Q.09: But only for $ r>0 $ big enough? Else $ CE \cap B_r(x) $ may be empty?

   Answer: Comes from the second inequality for minimizers (2.2)

6. Q.10: Complete proof of theorem 5.1... and Section 5

   Answer: See notes

7. Q.11: Why are we able to use lemma 3.1?
   
   Answer: Take M very small


### Material
- Claudia Bucur, Luca Lombardini, and Enrico Valdinoci, Complete stickiness of nonlocal
  minimal surfaces for small values of the fractional parameter (MR3926519) 
- Matteo Cozzi, On the variation of the fractional mean curvature under the effect of C
  1,α perturbations (MR3393254)
- Standard literature for theory of minimal surfaces (local)



## 05.12.23 (Third Meeting)


### ToDo's
- [ ] How to adress Prof. Cicalese/ Marco
- [ ] Registration of thesis (fill out PDF)
- [ ] Asking for PhD position