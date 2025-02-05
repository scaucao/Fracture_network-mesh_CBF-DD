# Fracture_network-mesh_CBF-DD
This repository contains the mesh file for the numerical example "Example 3: Flow through a 2D porous media with fracture network" from the paper:

S. Carrasco, S. Caucao, and G.N. Gatica: New mixed finite element methods for the coupled convective Brinkman-Forchheimer and double-diffusion equations. Journal of Scientific Computing, vol. 97, 3, article: 61, (2023).
Available in: <a href="https://doi.org/10.1007/s10915-023-02371-7" target="_blank">10.1007/s10915-023-02371-7</a>

To load the mesh in FreeFEM, use the code:

mesh Th = readmesh("Fracture-mesh.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

2: right boundary

3: top boundary

4: left boundary
