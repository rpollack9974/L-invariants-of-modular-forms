This directory contains files of the form Gamma0-M_all.csv.  

Each such file contains the data of the slopes ($p$-adic valuations) of the $\mathcal L$-invariants of forms of level $M$ with respect to all primes such that $p||M$.

The columns of the csv file are labelled as:

p,	Nnew,	k,	LMFDB_label,	sLinv,	sLderiv,	sLval,	twist,	ap_sign,	rhobar,	epp,	fpp

Here is what these means:

- p = prime
- Nnew = level of the eigenform (so $p || Nnew$)
- k = weight 
- LMFDB_label = LMFDB label of the eigenform
- sLinv = slope of the $\mathcal L$-invariant of the eigenform, with respect to the normalized $\mathfrak P$-adic valuation, for some (unspecified) prime $\mathfrak P$ above $p$ in the Hecke field of the eigenform
- sLderiv = slope of the derivaitive (with respect to...) of $p$-adic $L$-function at the central value (used to compute $\mathcal L$-invariant)
- sLval = slope of the algebraic part of the central value (with respect to...) of the complex $L$-series (used to compute $\mathcal L$-invariant)
- twist = conductor of the quadratic character used to twist to ensure the complex $L$-value is non-zero
- ap_sign = the sign of $a_p$ of the eigenform (only +/- 1)
- rhobar = a list whose entries are of the form q,[a_n,...,a_0] that represents minimal polynomial of $a_q\mod \mathfrak P$ --- namely the min poly should be $\sum_i a_i x^i$
- epp = ramification index of $\mathfrak P$ over $p$
- fpp = interial degree of $\mathfrak P$ over $p$

_Note_: Some of the headers may be in a different order.

Here is also a table listing the minimum and maximum weights and total number of data, in each file.

| Level      | Minimum weight | Maximum Weight | Number data | Missing weight(s) |
| ---------- | -------------- | -------------- | ----------- | ----------------- |
| Gamma0(2)  | 8              | 804            | 13466       |                   |
| Gamma0(3)  | 6              | 508            | 10752       |                   |
| Gamma0(5)  | --             | --             | --          |                   |
| Gamma0(6)  | 4              | 350            | 10033       | 346 (p=3), 348    |
| Gamma0(7)  | 4              | 290            | 10512       |                   |
| Gamma0(10) | 4              | 282            | 12437       | 268, 272, 276, 280 (both p) and 274 (p=5)         |
| Gamma0(11) | 4              | 200            | 8332        |                   |
| Gamma0(13) | 4              | 174            | 7433        | 136               |
| Gamma0(14) | 2              | 266            | 8071        | 252,256-264 (p=2) |
| --         | 2              | 204            | 4085        | 166, 174, 178-180, 186-190, 194-202 (p=7) |
| Gamma0(15) | 4              | 148            | 7188        | 84                |
| Gamma0(21) | 4              | 142            | 10080       |                   |
| Gamma0(33) | 2              | 84             | 5882        |                   |
| Gamma0(35) | 2              | 82             | 6726        |                   |
| Gamma0(45) | 2              | 112            | 5226        |                   |
| Gamma0(51) | 2              | 88             | 10100       | 86 (p=3)          |
| Gamma0(70) | 6              | 44             | 1834        | 44 (p=7)          |
| Gamma0(85) | 2              | 72             | 6913        |                   |
| Gamma0(105)| 4              | 54             | 8736        |                   |

_Note_: Each eigenform has an $\mathcal L$-invariant at each prime dividing the level. The number of data is therefore not the number of eigenforms, but the number of eigenforms times the number of distinct prime divisors.
