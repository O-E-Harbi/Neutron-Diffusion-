# Project Title: Exploring Neutron Diffusion in Nuclear Reactors

### Description:

This project delves into the fascinating world of neutron diffusion, a critical phenomenon in nuclear reactor physics.   Through a series of computational simulations and visualizations, we explore how neutrons distribute themselves within reactors of varying geometries and boundary conditions.   The project utilizes Python and libraries like **NumPy, SciPy, Matplotlib, and Plotly** to solve the time-dependent neutron diffusion equation and create informative 2D and 3D plots. The coefficients used in the simulations are taken from the article "Neutron Diffusion" by Graham W. Griffiths.

### Key Features:

- **Multi-Dimensional Analysis:** The project covers neutron diffusion in 1D, 2D, and 3D Cartesian coordinates, as well as 3D cylindrical and spherical coordinates.
- **Boundary Conditions:** Examines both Dirichlet (zero flux) and Neumann (zero flux gradient/reflective) boundary conditions, demonstrating their impact on neutron behavior.
- **Analytical and Numerical Solutions:** Employs analytical solutions where possible (1D and 2D Cartesian cases) and numerical methods (finite differences, root-finding) for more complex scenarios.
- **Interactive Visualizations:** Utilizes Matplotlib for 2D heatmaps and Plotly for interactive 3D surface and isosurface plots, providing intuitive insights into neutron density distributions.
- **Mode Analysis:** Investigates the contributions of different spatial modes (fundamental and higher-order) to the overall neutron density.
- **Time Evolution:** Demonstrates the time-dependent decay of neutron density due to absorption and leakage.

### Intended Audience:

- Students and researchers in nuclear engineering and reactor physics.
- Anyone interested in computational modeling and visualization of physical phenomena.

### How to Use:

- Clone the repository.
- Install the required libraries ( pip install -r requirements.txt).
- Run the Python scripts to generate the visualizations.
- Explore the code and modify the parameters to investigate different scenarios.

### References:

Griffiths, Graham W. "[Neutron diffusion](https://www.researchgate.net/publication/323035158_Neutron_diffusion).February 2018

### Disclaimer:

This project is intended for educational and research purposes. It provides a simplified model of neutron diffusion and should not be used for critical safety or design calculations without further validation and verification.

### Contributions:

Contributions and suggestions for improvements are welcome!
