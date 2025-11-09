# Nakajima's representation of the Heisenberg algebra

## Talk plan

0. (Aim.) Formulation of Nakajima's formula.

1. (Heisenberg algebra.) Recall our construction and Fock representation
of the Heisenberg algebra.

**Talk strategy: items 2 and 3 below will be skipped
and explained in practice at items 4 and 5**

2. (Borel-Moore homology.) BM homology is like singular homology
but admitting locally infinite singular chains. Unlike singular homology,
admits pushforwards AND pullbacks for certain maps.

Key properties:

    1. (Pushforward.) Only for proper maps.
    2. (Pullback.) Only for locally trivial fibrations.
    3. (Fundamental class.)
    4. (Intersection pairing.)

Other properties:

    - (Compact gives isomorphism.)
    - (Poincaré duality with (relative?) simplicial cohomology.)

3. (Correspondences.) Given a product of schemes X1 x X2 
such that the projection p_2 to X2 is proper, 
we can associate to any homology class 
(in particular to the fundamental class of any subvariety Z) 
in H_*(X1 x X2) an operator H_i(X2) \to H_{nonsense}(X1).

We also have composition of correspondences,
given essentially by pulling back classes and intersecting
at a triple product.

4. (Worked example.) Pick alpha = [X] and beta = [{x}] for some point x\in X.
For any set of n distincts points x1,...,xn \in X \ {x},
which can be thought of as an ideal I in the Hilbert scheme,
we compute the commutation relation

[ P_alpha [1] , P_beta [ -1]] (I) = I.

5. (Sketch of proof.) Proof of case i,j>0 by unrolling definitions
and proving two claims, I'm almost done with this.

6. (Götsche's formula.) Pending_

## Caveats

1. The Poincaré duality of BM is not explained, though used, by Nakajima.
In videos Anthony explains there's a duality with *relative* singular
cohomology. (This rather technical remark can be skipped if we just
assume X is projective).

2. The mysterious appearence of the (-1)^{something} in the main formula,
and its relation to a super version of Heisenberg algebra.

3. Why is P_alpha[i] a subvariety - we don't consider its Zariski closure!

4. P[i,j] is introduced as a "set theoretical intersection",
but then Claim 1 describes an "isomorphism" between
P[i,j] \cap {x≠y} and P[j,i] \cap {x≠y}.
Is this only a bijection, i.e. isomorphism in (Sets)?

5. In the proof of Claim 1, how can we make sure that J_2' is uniquely
defined? That was the point of the Hilbert-Chow morphism,
we know there are points in the Hilbert scheme that
are not uniquely determined as sets of points with multiplicities.

## To do

1. Clean up the Hilbert scheme section: too many Stack Exchange references!

2. Add explanation of the fat point and tangent directions.

3. Finish proof of Claim (2).

4. Göttsche's formula.

5. Clean up!
