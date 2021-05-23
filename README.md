 algcurve.lib is a [Singular](https://www.singular.uni-kl.de/) library to compute a standard basis of an algebroid curve over an algebraically closed field and a set of generators of its associated semering. 
 This package is a part of the master thesis  "An algorithm to compute the associated Semiring to an Algebroid Curve" by George Krait, TU Kaiserslautern 2017 (see [2])
 
 category= Commutative Algebra.
 
Installation: After installing Singular (see [here](https://www.singular.uni-kl.de/index.php/singular-download.html)) and run it,  the user needs to
import the library curvepar_lib using the command:

LIB "curvepar.lib";
Then the user can import algcurve.lib by the command:
LIB "curvepar.lib";


A detailed documentation about how to use the procedures can be found inside the file algcurve.lib. 




AUTHORS:  George krait,  georgekrait@yahoo.com.



KEYWORDS: singularities, algebroid curve, semiring.


SEE ALSO: curvepar_lib




PROCEDURES:

-) algcurstd(P):          standard basis of algebroid curve with parametrization P.

-) algcursemiring(P):      value semi-ring of algebroid curve with parametrization P.

-) algcursemigrpcls(P):   the topological closure of algcursemiring(P).

-) algcurmember(f, P):    checks whether f in the curve defined by P.

-) algcursmallgamma(P):   all elements of the value semigroup which are less than the conductor.



REFERENCES:

[1] E.Carvalho, M.E.Hernandes: The Semiring of Values of an Algebroid Curve.

[2] G.Krait: An algorithm to compute the associated Semiring to an Algebroid Curve.
