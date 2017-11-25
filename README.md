# extlaplace
Inverse Laplace transforms for Maxima

The package depends on several special functions 
Mittag-Leffler -  3 parameter
Mittag-Leffler  - 2 parameter
Mittag-Leffler  - classical (1 parameter)
hypergeometric functions - pFq
and the Mainardi-Wright function.

These functions arise naturally in solving PDEs using the Laplace transform technique.
In addition Bessel function are also useful.

All patterns of these functions are recognized and then the transform is looked up in term of a special function, which is then simplified.
That is for special choices of parameters the functions can be represented by elementary functions or by more conventional special functions (e.g. gamma incomplete, erf etc).

The philosophy is similar to the Sympi implementation but in the latter case Sympi uses mostly the Fox H function, (i.e. Mellin transform), which is more counter intuitive to work with. 

