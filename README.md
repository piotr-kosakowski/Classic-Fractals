# Classic fractal's modifications

In this project we implemented two classic fractals, both being space-filling curves, i.e. Hilbert curve and Peano curve.

Space-filling curve is a kind of function that for every point on unit interval ($$[0; 1]$$) corresponds to every point on unit square ($$[0; 1] \times [0; 1]]$$).
We implemented these two curves recursively, as their respective definitions are recursive too. That means, that what you see is not space-filling curve itself, but its iterations, which with number of iterations tending to infinity will grant space-filling curve.

What are they for? Well, Peano curve was invented by mathematician Giuseppe Peano for his interest in prooving Cantor's statement that $$\displaystyle\mathop{\forall}_{n \in \mathbb{N}}\|\mathbb{R}\| = \|\mathbb{R}^n\|$$.
Though his curve is not bijection, it still proves this cardinality equation, while Hilbert curve is used in reduction of data dimensions.

There are some examples:

![Hilbert curve first iteration](img/hilbert_classic_1.png "Some iterations of Hilbert curve")
![Hilbert curve second iteration](img/hilbert_classic_2.png "Some iterations of Hilbert curve")
![Hilbert curve third iteration](img/hilbert_classic_3.png "Some iterations of Hilbert curve")

![Peano curve first iteration](img/peano_classic_1.png "First iteration of Peano curve")
![Peano curve second iteration](img/peano_classic_2.png "First iteration of Peano curve")
![Peano curve third iteration](img/peano_classic_3.png "First iteration of Peano curve")

We also developed several modifications for both of these fractals based on starting shape or construction change.

Developed by Piotr Kosakowski and Michał Legczylin.
