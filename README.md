# Fracture_network-mesh_CBF-DD
This repository contains the mesh file for the numerical example: "Example 3: Flow through a 2D porous media with fracture network" of the work:

S. Carrasco, S. Caucao, and G.N. Gatica: New mixed finite element methods for the coupled convective Brinkman-Forchheimer and double-diffusion equations. Preprint 2023-16, Centro de Investigación en Ingeniería Matemática (CI²MA), Universidad de Concepción, (2023). 

Available in: <a href="https://ci2ma.udec.cl/publicaciones/prepublicaciones/prepublicacionen.php?id=522" target="_blank">https://ci2ma.udec.cl/publicaciones/prepublicaciones/prepublicacionen.php?id=522</a>

To load the mesh in FreeFem++, use the code:

mesh Th = readmesh("Fracture-mesh.msh");


Labels setting:

33: region outside the fracture

34: region inside the fracture

1: bottom boundary

2: right boundary

3: top boundary

4: left boundary
