# HillsEquation_examples
Some examples for computing solutions to Hills equations (periodic)


Computes the eigenvalues and eigenfunctions of a type of Hill's equation studied by Strutt M (1948). The even eigenvalue problem is determined by

<div align="center">
$
\frac{d^2\phi_{2n}}{dy^2} + \left[a_{2n} - qU(2y) \right]\phi_{2n} = 0
$
</div>
subject to periodic boundary conditions

<div align="center">
$
\left.\frac{d\phi_{2n}}{dy}\right|_{y=0}  = \left.\frac{d\phi_{2n}}{dy}\right|_{y=\pi}=0
$
</div>

and odd eigenvalue problem is determined by

<div align="center">
$
\frac{d^2\phi_{2n+2}}{dy^2} + \left[b_{2n+2} - qU(2y) \right]\phi_{2n+2} = 0
$
</div>
which, in turn is subject to the periodic boundary conditions

<div align="center">
$
\left.\phi_{2n+2}\right|_{y=0}  = \left.\phi_{2n+2}\right|_{y=\pi}=0
$
</div>

The function $U(2y)$ is an integrable and periodic function, and $q$ is a purely imaginary parameter.