---
layout: page
title: Master Thesis
permalink: /publications/kuthesis/
---
## Lagrange-Galerkin Schemes for Groundwater Contaminant Models

This thesis addresses the critical issue of groundwater contamination. The model consists of two coupled equations: the **advection-diffusion equation** and the **Stokes equation**.
{: style="text-align: justify"}

<div style="display: flex; justify-content: center; gap: 24px; flex-wrap: wrap;">
  <div style="text-align: center;">
    <img src="../../assets/lg-real.png" alt="Real Domain" style="max-width: 300px; width: 100%;">
  </div>
  <div style="text-align: center;">
    <img src="../../assets/lg-mesh.png" alt="Numerical Domain" style="max-width: 300px; width: 100%;">
  </div>
</div>
<div style="text-align: center; font-size: 0.9em; color: #555; margin-top: 0.5em;">
  <em>The study area, shown via satellite imagery (left), and the corresponding discretized numerical domain (right) used for the simulation.</em>
</div>

## Numerical Methods
- **Spatial Discretization**  
To solve this system of equations numerically, the **Lagrange-Galerkin** scheme is used. This is a specific type of finite element method (FEM) that is well-suited for problems where advection term is a dominant factor. The method is chosen for its stability.

- **Implementation**
The model was developed using the [FreeFEM](https://freefem.org/).
{: style="text-align: justify"}

