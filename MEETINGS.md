# 07.11.23 (Initial Meeting)

Fumihiko will give me a paper Preliminaries should already be there Stop with current
paper (Mean curvature flow) (maybe later relevant) Start easier paper
([2009_caffarelli](literature/2009_caffarelli-roquejoffre-savin_nonlocal_minimal_surfaces.pdf))

## Idea

Extention of Perimeter => Fractional Perimeter kind of gives the "Area of the boundary
times some potential factor"

Fractional Perimeter is also called nonlocal perimeter, because we need to consider not
just the elements at the boundary, but also those around it (not locally anymore)

We consider problems of the type $min P_s (E; \Omega)$ over those sets $E$ which have
fixed boundary $E \setminus \Omega = E_0$ outside of $\Omega$. We are interested in the
local perimeter problem $min P (E; \Omega)$, but first consider the nonlocal perimeter
problem. Existence and Regularity proved by
[2009_caffarelli](literature/2009_caffarelli-roquejoffre-savin_nonlocal_minimal_surfaces.pdf),
but we don't know how those minimizer look like yet.

Expected Behavior of minimizer, see in Paper
[2016_dipierro](literature/2016_dipierro-savin-valdinoci_graph_properties_for_nonlocal_minimal_surface.pdf)
and
[2017_dipierro](literature/2017_dipierro-savin-valdinoci_boundary_behaviour_nonlocal_minimal_surface.pdf)
Interesting behavior when considering $\Omega$ a cylinder and $E_0$ the halfspace.

Look up Catenoid but these only apply in $\mathbb{R}^3$. See paper
[2022_DipierroOnoue](literature/2022_dipierro-onoue-valdinoci_(dis)connectedness_of_nonlocal_minimal_surfaces_in_a_cylinder_and_stickiness_property.pdf)

One possible direction of my thesis: First think about problemsetting and then Minimizer
shapes.

Maybe not consider whole halfplanes, but two cylinders with radius $R$ and let $R$ go to
$\infty$ (current research of Onoue). Behavior of the minimizer as $R$ go to $\infty$.

Template of Thesis from TUM.

# 21.11.23 (Second Meeting)

## Questions

1. Q.02: Why choose for $\Omega\_{k+1} = { u(x,\varepsilon) > \alpha }$, $\alpha = 0$
   (which increases $\Omega\_{k+1}$) and not $\alpha = 1/2$ which correspondences to
   motion by mean curvature, cf. Merriman etal 1992.

   Answer: Probably because the initial data is $u_k = ind\_\Omega - ind\_{C\Omega}$

2. Q.03: How does BM differ from Levy process, s.t. long-range correlation is considered
   in the later but not in the former? BM is as-cts, which Levy-Proceses are not in
   general

   Answer: The usual Laplacian $ \Delta u $ is locally, but the fractional Laplacian
   $(-\Delta) ^{\frac{s}{2}} u(x) := p.v. \int_{\mathbb{R}^n}
   \frac{u(x)-u(y)}{|x-y|^{d+s}}$ Ask Marco some more on MBO-Scheme

3. Q.07: Why are we looking at local minimizer again? We want nonlocal minimizers?

   Answer: Local in this case doesn't mean "local minimizer", but we restrict our setting
   to a bounded set $\Omega$ s.t. everything is still in $\Omega$. "Nonlocal Minimizer"
   means behavior of Boundary considering the whole boundary. I confused $E_0$ with
   $\Omega$.

4. Q.08: Minimizer in what sense? If $E_n \setminus B_1 = E_0$, then $(E_n \triangle E)
   \setminus B_1 = \emptyset$ (Don't understand rest of proof Thm 3.3)

   Answer: The set $E_0$ depends on $n$. The minimality doesn't specify the set outside of
   $\Omega$ or $B_1$ in our case.

5. Q.09: But only for $r>0$ big enough? Else $E^c \cap B_r(x)$ may be empty?

   Answer: Comes from the second inequality for minimizers (2.2)

6. Q.10: Complete proof of theorem 5.1... and Section 5

   Answer: See notes

7. Q.11: Why are we able to use lemma 3.1?

   Answer: Take M very small

## Material

- Claudia Bucur, Luca Lombardini, and Enrico Valdinoci, Complete stickiness of nonlocal
  minimal surfaces for small values of the fractional parameter (MR3926519)
- Matteo Cozzi, On the variation of the fractional mean curvature under the effect of
  C^1,α perturbations (MR3393254)
- Standard literature for theory of minimal surfaces (local)

# 05.12.23 (Third Meeting)

## ToDo's

- [x] Registration of thesis (fill out PDF)
- [x] Asking for PhD position or Recommendation Letter
- [x] How to draw graphics/ figures (Recommendations?) (e.g. Inkscape, Tikz, Geogebra,...)

## Idea

See Notes from 30.11.23

## Questions

- Bracke Flows for generation of Mean Curvature Flow
- To understand MBO scheme just read the original Paper on MBO by Merriman

## Topic

Idea: Consider Omega as the cube, but $E_0$ with radius $1$ (see whether we get the
Cylindrical structure) (Box plus cylinder and send $r$ to $\infty$) (for small and large
$M$) 2nd Idea: Consider problem as fumihiko but let $E_0$ be restricted vertically by $r$
(Fix $r$ and see whether there exist an $M$ st connected or even $E_M=E_0$)

# 19.12.23 (Third Meeting)

## What have I done so far?

### Model 01:

I showed that there exists an upper bound on $M$, s.t. the minimizer $E_M = \Omega \cup
E_0$. Almost exactly as Fumihiko did, one can show that the minimizer is disconnected
above some threshold. Interesting to see is the dependence on $r_0$. Going forward, one
could look at a specific $M$ for which Model 01 is not cylindrical but for Model 00 it is.
Could lead to some understanding of "stickiness property"

### Model 02:

I am showing upper bound, but I still need a bound on the negative term. Issue more
technical, than mathematical. I guess there could be some threshold where the minimizer is
cylindrical, but I am not sure here. Bound still depends on $R > M$, need something
smaller and (probably) prove disconnectedness. Next step would be to show disconnectedness
above some threshold, but more interesting is the behavior of $E_M$ for fixed $M$ and
increasing $R$. Could lead to some understanding of "stickiness property". Can we get some
quantification on $E_M$? When is $E_M$ connected for increasing $R$?

### Possible Idea going forward

Combine both Models to get an understanding of "Stickiness". Could maybe lead to
understand behavior of $E_M$ for arbitrary $E_0$ whose boundary is defined by some
function (Model the set with boxes of varying size). Is that even interesting?

## Questions

- [ ] Doubt about Eq (2.8) in Fumihiko Paper
  - Usage of Lemma 3.1 requires $R = r_0$ and a ring (depending whether $\Lambda M \geq 1$
    or not), else we don't have a superset
  - Upper Bound only works if $\Lambda M \geq 1$ (I think), then $\Lambda$ depends on $M$.
    Thus next step, where $\Lambda$ is chosen doesn't work anymore.  
- [ ] Issue with dependence on $r_0$ and on $\Lambda$

## Going forward

0. Send Fumihiko the Calculations of Model 01
1. Complete CV and send out first applications/ Ask prof for recommendation
2. Reading paper, get ideas for proofs and try to analyze behavior of $E_M$ for fixed $M$
   and increasing $R$ for both models with emphasize on "stickiness" 
3. Think about combining both models to try modeling behavior of $E_M$ for arbitrary $E_0$
   (box approximation idea) 
4. For Model 01: Does Stickiness depend on $R$?
5. For Model 01: If $R = 1$ does there exist an $M$ s.t. $E = E_0$?
6. If we have a minimizing set $E$ then the boundary of $E\setminus E_0 \subset \Omega$ is
   touching the boundary of $E_0$
7. For symmetric model is the minimzer symmetric as well?
8. What is the minimizer for dimension $1$ for both models?



# 23.01.24 (Fourth Meeting)

## Findings
1. For dimension $1$ the minimizer in model 01 and 02 is always connected (restriction on
   dimension needed? Does it even make sense for $n = 1$?)
2. For model 02: If $R > M$ there exists an $r_0 = \min\{R/2, 1\}$ s.t. the minimizer
   contains the tube of radius $r_0$. Don't need to show it for all $r \in (0,1)$ small
   enough, just the existence of one $r_0$, since if I can contradict the touching of that
   one, smaller can't touch as well
   1. Estimate of negative term is wrong...
3. The minimizer lies in the convex hull of $E_0$ for $\Omega$ compact (i.e. $E \setminus
   E_0 \subset \Omega \cap conv E_0$) __(wrong...)__
   1. I think, that's not a classical property of minimal surfaces, just found something
      with rather strict conditions (see 1970 Blaine Lawson,The global behavior of minimal
      surfaces $S^n$, https://www.jstor.org/stable/1970835)
4. The minimizer is symmetric (see 2017 Dipierro-Savin-Valdinoci Appendix Lemma A.1)
5. If $\Omega$ compact, the part of the minimizer in $\Omega$, i.e. $E \cap \Omega$ has to
   "touch" on a non-null set __(wrong...)__

## Ideas

1. Reading paper, get ideas for proofs and try to analyze behavior of $E_M$ for fixed $M$
   and increasing $R$ for both models with emphasize on "stickiness" 
2. Think about combining both models to try modeling behavior of $E_M$ for arbitrary $E_0$
   (box approximation idea)
3. For Model 01: Does Stickiness depend on $R$?
4. For Model 01: If $R = 1$ does there exist an $M$ s.t. $E = E_0$?
5. For Model 02: Do we have "stickiness" for small $R$?
6. For Model 02: For fixed $R$, when does the topology of the minimizer change?
7. For Model 02: For fixed $M$, does there exist an $R$ s.t. $E = E_0$?
8. For Model 02: Is there an $R < 2$ s.t. $E = E_0 \cup \Omega$?
9. Idea: Construct some sort of algorithm to find minimizer (use compactness of $\Omega$)

## Going forward

1. For model 02: Negative term is wrong, need to find a better estimate
2. If distance between $E_0$ and $\Omega$ is non-zero and $\Omega$ compact, then $E = E_0$
   else surface unnecessarily increased? Inequality was wrong...
   1. Kinda stuck here... Tried various methods to compare $E$ with $E_0$
   2. One idea motivated by
      [2016_Dipierro](literature/2016_dipierro-savin-valdinoci_graph_properties_for_nonlocal_minimal_surface.pdf),
      another idea motivated by
      [2016_Lombardini](literature/2016_lombardini_approximation_of_sets_of_finite_fractional_perimeter_by_smooth_sets_and_comparison_of_local_and_global_s-minimal_surfaces.pdf)

# 06.02.24 (Fifth Meeting)

## What have I done
1. For Model 02: Adjusted computation to prove, that minimizer is connected for small $M$,
   by considering half circle and moving it.
2. For arbitrary $E_0$, $E_1 = B_\epsilon$ non-touching, the minimizer is $E_0$
   1. Need to extend the idea to arbitrary $E_1$, maybe per compactness and covering? 
   2. Use Covering and handle interactions (Isoperimeter)

## Ideas
1. What is the critical $M_0$ s.t. above disconnected and below connected
   1. Consider the barrier of Minimizer (mean curvature)
   2. Construct a set of Zero Mean Curvature (see in Dipierro-Savin-Valdinocci, about
      Halfplane with bumps and Stickiness)
2. For Model 01: Use general functions as the bound of $E_0$
3. For both Models: Generalize by saying, that I only need a box inside $E_0$ (maybe just
   mention in the thesis

# 27.02.24 (Sixth Meeting)

Need reference letter ASAP from both if possible (send to br607@georgetown.edu)

Stuck on proof...