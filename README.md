# GA

GA destroys common conceptions of matrix algebra, calculus and curve fitting in euclidean space with coordinates

- vector derivative $\nabla F$
- deep relations in between multivariate calculus and projective geometry: regression, regularization, normal equations, jacobian, hessian, method of gradient descent is a projection onto a jacobian hyperplane
- differentials define linear, adjoint
- matrix algebra is subalgebra to GA; $a_{ik}=e_i \dot a_k$ as a inner product of two n-vectors and determinants as expansions -> Cramers rule to solve Ax=b (which is usually taught to be solved by Gaussian matrix algorithm, but can be solved with $A^{-1}=\frac{adj(A)}{det(A)})
- Tensors defined as frame independent linear function
- nothing special with Paulis
- python: clifford, galgebra
- a vector manifold is a set with tangent space and a pseudoscalar at any point; it allows to do coordinate free calculus 


- Doran (2003): Geometric Algebra for Physicists [1](http://deferentialgeometry.org/papers/Doran,%20Lasenby%20-%20Geometric%20Algebra%20for%20Physicists%20(2003).pdf)
- Sobczyk (2021): Nested coordinate systems [2](https://arxiv.org/pdf/2101.00976.pdf)
- Hestenes (2015): Tutorial [3](https://www.youtube.com/watch?v=ItGlUbFBFfc)
- Dorst (2010): Geometric Algebra for Computer Science [4](https://cs.uwaterloo.ca/~smann/GA/someanswers.pdf)
- Dorst (2019): Marquardt Levenberg algorithm [5](https://www.researchgate.net/profile/Steven-De-Keninck/publication/333704791_Geometric_Algebra_Levenberg-Marquardt/links/60f6fff3fb568a7098c3c633/Geometric-Algebra-Levenberg-Marquardt.pdf) using automatic differentiation based on Dual Numbers and presents to use the outer product instead of Gaussian elimination

# PGA

in PGA, each plane is described by a 1-vector, and if there exists one solution, they intersect
In PGA, Ax=b then is just an n-vector formed by the outer product of the 1-vectors

# Lie Algebras as the essence of physics, symplectic manifolds

- the SU2 spin group has a Lie algebra which is quantum mechanics, spinors are included in GA
- classical physics has something with the symplectic group and it's Lie Algebra 
