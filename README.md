# TSpreadIdeals
A Macaulay2 package to deal with t-spread ideals of a polynomial ring. Please find more details about the package in this [paper](https://arxiv.org/abs/2110.11801).  

Introduction
===================
The algorithms implemented in the package `TSpreadIdeals` are devoted to manage t-spread monomials and t-spread ideals of a polynomial ring.

- Some auxiliary routines allow the user to check which t-spread class a monomial belongs to, or to sieve all the t-spread monomials from a list of monomials. Furthermore, there is a function giving the possibility to compute the t-spread shadow of a list of monomials.
- It is possible to obtain the smallest t-strongly stable set of monomials or the smallest t-lex set containing a set of t-spread monomials. The package also provides some methods to compute the cardinality of the aforementioned sets.
- Some functions allow to solve the [problem](https://arxiv.org/abs/2105.11944) of determining if a given configuration (a r-tuple of pairs of integers and a r-tuple of integers) represents an admissible configuration for the `extremal Betti numbers` of a t-strongly stable ideal. In the case of a positive answer, it is possible to build the smallest t-strongly stable ideal with the given configuration of extremal Betti numbers.
- The package allows to manage a [generalization](https://arxiv.org/abs/1811.00798) of the `Kruskal-Katona's theorem` by computing the f_t-vector of a t-spread strongly stable ideal. Moreover, it is possible to state whether a sequence of integers is the f_t-vector of a suitable t-spread ideal. In the affirmative case, it is possible to build the smallest t-lex ideal whose f_t-vector coincides with the given sequence.  
