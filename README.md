# Stable-homology-of-braid-groups-and-moduli-of-hyperelliptic-curves

Data computed in connection with the article [BDPW]: *Hyperelliptic curves, the scanning map, and moments of families of quadratic L-functions*, arXiv:2302.07664, by Jonas Bergström, 
Adrian Diaconu, Dan Petersen and Craig Westerland.

## Description of data 

This data set contains dimensions of stable homology groups of the braid group and of the moduli space of hyperelliptic curves, with coefficients in a local system of small weight. It was computed using Theorem 1.1.6 and Corollary 10.0.9 of [BDPW], which gives a formula for such dimensions for any local systems, as well as the algorithm coming from Lemma 13.6 of "J. Bergström, Equivariant counts of points of the moduli spaces of pointed hyperelliptic curves, Documenta Mathematica, 14, (2009), 259-296".

-The file "StabBraidLoc.txt" contains the generating series \sum_{k} \dim H_k(\beta_{infty},S^{\lambda}(V)) (-z)^k, as a rational function, for all local systems lambda with |\lambda| \leq 20 and with \lambda(1) \leq |\lambda|/2, with notation coming from [BDPW].

-The file "StabHypLoc.txt" contains the generating series \sum_{k} \dim H_k(H_{infty},V_{\lambda}) (-z)^k, as a rational function, for all local systems lambda with |\lambda| \leq 20 and with \lambda(1) \leq |\lambda|/2, with notation coming from [BDPW].

Note that by Theorem 7.0.6 together with Theorem 10.0.12 of [BDPW] we know that \dim H_k(\beta_{infty},S^{\lambda}(V))=\dim H_k(H_{infty},V_{\lambda})=0 when \lambda(1) > |\lambda|/2. 

-The file "cohBraidlocNonzero.txt" contains a list of all [lambda,\dim H_k(\beta_{infty},S^{\lambda}(V))] such that \dim H_k(\beta_{infty},S^{\lambda}(V)) is non-zero for k=1,..,5, using Theorem 7.0.2 of [BDPW].

-The file "cohHyplocNonzero.txt" contains a list of all [lambda,\dim H_k(H_{infty},V_{\lambda})] such that \dim H_k(H_{infty},V_{\lambda}) is non-zero for k=1,..,5, using Remark 10.0.13 of [BDPW].
