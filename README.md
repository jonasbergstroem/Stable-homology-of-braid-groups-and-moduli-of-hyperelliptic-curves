# Stable-homology-of-braid-groups-and-of-moduli-of-hyperelliptic-curves

Data computed in connection with the article [BDPW]: *Hyperelliptic curves, the scanning map, and moments of families of quadratic $L$-functions*, arXiv:2302.07664, by Jonas Bergström, 
Adrian Diaconu, Dan Petersen and Craig Westerland.

## Description of data 

This data set contains dimensions of stable homology groups of the moduli space of hyperelliptic
curves with coefficients in a local system of small weight. It was computed using Corollary 10.0.9
of [BDPW]: "J. Bergström, A. Diaconu, D. Petersen and C. Westerland, Hyperelliptic curves, the
scanning map, and moments of families of quadratic $L$-functions, arXiv:2302.07664"
which gives a formula for such dimensions for any local systems, as well as the algorithm coming
from Lemma 13.6 of "J. Bergström, Equivariant counts of points of the moduli spaces of pointed
hyperelliptic curves, Documenta Mathematica, 14, (2009), 259-296".

-The file "StabHypLoc.txt" contains the generating series \sum_{k} \dim H_k(H_{infty},V_{\lambda}) (-z)^k,
as a rational function, for all local systems lambda with |\lambda| \leq 20 and with \lambda(1) \leq |\lambda|/2,
with notation coming from [BDPW].

By Theorem 7.0.6 together with Theorem 10.0.12 of [BDPW] we know that \dim H_k(H_{infty},V_{\lambda})=0 when
\lambda(1) > |\lambda|/2. 
