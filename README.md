# Graphene Phonon Dispersion Band Structure with Central Force Model
The project only relies on the basic configurations of Lattice Vector and Basis Vectors of Atoms. Then by running the "grapheneCentralForceModel.ipynb" cell by cell, you will get everything as shown below. You can choose your own Lattice Vector and Basis Vectors of Atoms instead, which should yield the same graphs for graphene. For other materials, as long as it only has lattice basic vectors and two basic vectors, the program could handle that, but you may modify the k-space coordinates to get accurate dispersion.

## Basic Configurations (you can change and choose your own):
![](imgs/configs.png)

## Unit Cell, Atom Basis Vectors, and Reciprocal Lattice (you can change and choose your own):
<img src="imgs/unitcells.png" width="40%">.
<img src="imgs/kspace.png" width="40%">.

## Potential Energy, Constant Force Matrix, Dynamical Matrix, and Eigenvalues:
![](imgs/expressions.png)

## Phonon Dispersion Band Structure along Γ-M-K-Γ:
<img src="imgs/dispersion.png" width="50%">.

## Contours of Dispersion in k-space
<img src="imgs/contour.png" width="50%">.

## Cropped Contours of Dispersion in First Brillouin Zone of k-space
<img src="imgs/contourcropped.png" width="50%">.

## Density of States (DOS) and Specific Heat Capacity (Cv)
<img src="imgs/dos.png" width="40%">.
<img src="imgs/cv.png" width="40%">.
