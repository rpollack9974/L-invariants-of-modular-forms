This directory contains files of the form Gamma0-N_all.csv.  Each such file contains the data of the slopes of the $\mathcal L$-invariants of forms of level $N$ with respect to all primes such that $p||N$.

The columns of the csv file are labelled as:

p,	Nnew,	k,	LMFDB_label,	sLinv,	sLderiv,	sLval,	twist,	ap_sign,	rhobar,	epp,	fpp

which now explain.

p = prime <br>
Nnew = level of the modular form (so $p || Nnew$)<br>
k = weight <br>
LMFDB_label = LMFDB label of the modular form<br>
sLinv = $p$-adic valuation of $\mathcal L$-invariant at some prime $\mathfrak P$ over $p$ in the Hecke field of the modular form<br>
sLderiv = $p$-adic valuation of special value of the $p$-adic $L$-function used to compute $\mathcal L$-invariant<br>
sLval = $p$-adic valuation of special value of the complex $L$-function used to compute $\mathcal L$-invariant
  the exceptional zero conjecture gives taht sLinv = sLderiv - sLval<br>
twist = conductor of the quadratic character used to twist to ensure the complex $L$-value is non-zero<br>
ap_sign = the sign of $a_p$ of the given modular form<br>
rhobar = a list whose entries are of the form q,[a_n,...,a_0] which represents the fact that the minimal polynomial of $a_q\mod \mathfrak P$ is $\sum_i a_i x^i$<br>
epp = ramification index of $\mathfrak P$ over $p$ <br>
fpp = interial degree of $\mathfrak P$ over $p$


