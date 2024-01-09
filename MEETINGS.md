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

1. Q.02: Why choose for $ \Omega\_{k+1} = { u(x,\varepsilon) > \alpha } $, $ \alpha = 0 $
   (which increases $ \Omega\_{k+1} $) and not $ \alpha = 1/2 $ which correspondences to
   motion by mean curvature, cf. Merriman etal 1992.

   Answer: Probably because the initial data is $ u_k = ind\_\Omega - ind\_{C\Omega} $

2. Q.03: How does BM differ from Levy process, s.t. long-range correlation is considered
   in the later but not in the former? BM is as-cts, which Levy-Proceses are not in
   general

   Answer: The usual Laplacian $ \Delta u $ is locally, but the fractional Laplacian $
   (-\Delta) ^{\frac{s}{2}} u(x) := p.v. \int_{\mathbb{R}^n}
   \frac{u(x)-u(y)}{|x-y|^{d+s}} $
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

- Claudia Bucur, Luca Lombardini, and Enrico Valdinoci, Complete stickiness of nonlocal minimal surfaces for small values of the fractional parameter (MR3926519)
- Matteo Cozzi, On the variation of the fractional mean curvature under the effect of C 1,α perturbations (MR3393254)
- Standard literature for theory of minimal surfaces (local)

## 05.12.23 (Third Meeting)

### ToDo's

- [x] Registration of thesis (fill out PDF)
- [x] Asking for PhD position or Recommendation Letter
- [x] How to draw graphics/ figures (Recommendations?) (e.g. Inkscape, Tikz, Geogebra,...)

### Idea

See Notes from 30.11.23

### Questions

- Bracke Flows for generation of Mean Curvature Flow
- To understand MBO scheme just read the original Paper on MBO by Merriman

### Topic

Idea: Consider Omega as the cube, but E0 with radius 1 (see wether we get the Cylindrical
structure) (Box plus cylinder and send r to infty) (for small and large M)
2nd Idea: Consider problem as fumihiko but let E0 be restricted vertically by r
(Fix r and see wether there exist an M st connected or even EM=E0)

## 19.12.23 (Third Meeting)

### What have I done so far?

#### Model 01:

I showed that there exists an upper bound on $ M $, s.t. the minimizer $ E_M =
\Omega \cup E_0 $.\
Almost exactly as Fumihiko did, one can show that the minimizer is disconnected above some
threshold.\ 
Interesting to see is the dependence on $ r_0 $.\ 
Going forward, one could look at a specific $ M $ for which Model 01 is not cylindrical
but for Model 00 it is.\
Could lead to some understanding of "stickiness property"

#### Model 02:

I am showing upper bound, but I still need a bound on the negative term. \
Issue more technical, than mathematical. I guess there could be some threshold where the
minimizer is cylindrical, but I am not sure here. Bound still depends on $ R > M $, need
something smaller and (probably) prove disconnectedness. \
Next step would be to show disconnectedness above some threshold, but more interesting is
the behavior of $ E_M $ for fixed $ M $ and increasing $ R $.\
Could lead to some understanding of "stickiness property". Can we get some
quantification on $ E_M $? When is $ E_M $ connected for increasing $ R $?

#### Possible Idea going forward

Combine both Models to get an understanding of "Stickiness".\
Could maybe lead to understand behavior of $ E_M $ for arbitrary $ E_0 $ whose boundary is
defined by some function (Model the set with boxes of varying size).\
Is that even interesting?

### Questions

- [ ] Doubt about Eq (2.8) in Fumihiko Paper
  - Usage of Lemma 3.1 requires $R = r_0$ and a ring (depending whether $ \Lambda M \geq
    1 $ or not), else we don't have a superset 
  - Upper Bound only works if $ \Lambda M \geq 1 $ (I think), then $ \Lambda $ depends
    on $ M $. Thus next step, where $ \Lambda $ is chosen doesn't work anymore.  
- [ ] Issue with dependence on $ r_0 $ and on $ \Lambda $

### Going forward

0. Send Fumihiko the Calculations of Model 01
1. Complete CV and send out first applications/ Ask prof for recommendation
2. Reading paper, get ideas for proofs and try to analyze behavior of $ E_M $ for fixed $
   M $ and increasing $ R $ for both models with emphasize on "stickiness" 
3. Think about combining both models to try modeling behavior of $ E_M $ for arbitrary $
   E_0 $ (box approximation idea) 
4. For Model 01: Does Stickiness depend on $ R $?
5. For Model 01: If $ R = 1 $ does there exist an $ M $ s.t. $ E = E_0 $?
6. If we have a minimizing set $ E $ then the boundary of $ E\setminus E_0 \subset \Omega $
   is touching the boundary of $ E_0 $
7. For symmetric model is the minimzer symmetric as well?
8. What is the minimizer for dimension $ 1 $ for both models?



## 09.01.24 (Fourth Meeting)

### Findings
1. For dimension $ 1 $ the minimizer in model 01 and 02 is always connected (restriction on
   dimension needed?)
2. For model 02: If $ R > M $ there exists an $ r_0 = \min\{R/2, 1\} $ s.t. the minimizer
   contains the tube of radius $ r_0 $ \
   Don't need to show it for all $ r \in (0,1) $ small enough, just the existence of one $
   r_0 $, since if I can contradict the touching of that one, smaller can't touch as well
3. The minimizer lies in the convex hull of $ E_0 $ (i.e. $ E \setminus E_0 \subset
   \Omega \cap conv E_0 $) __**(IF inequality is correct)**__
   1. I think, that's not a classical property of minimal surfaces, just found something
      with rather strict conditions (see 1970 Blaine Lawson,The global behavior of minimal
      surfaces $ S^n $, https://www.jstor.org/stable/1970835)
4. The minimizer is symmetric (see 2017 Dipierro-Savin-Valdinoci Appendix Lemma A.1)