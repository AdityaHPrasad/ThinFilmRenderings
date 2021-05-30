# Physically Based Rendering Techniques to Visualize Thin-Film Smoothed Particle Hydrodynamics Fluid Simulations
## Papers
- **research paper:** [Thin-Film Smoothed Particle Hydrodynamics Fluid](https://cs.dartmouth.edu/~bozhu/papers/sph_bubble.pdf)
- **undergraduate thesis paper:** [Physically Based Rendering Techniques to Visualize Thin-Film Smoothed Particle Hydrodynamics Fluid Simulations](/Aditya_Thesis_Draft4.pdf)


## Abstract

This [thesis](/Aditya_Thesis_Draft4.pdf) introduces a methodology and workflow I developed to
visualize smoothed hydrodynamic particle based simulations for the
research paper [’Thin-Film Smoothed Particle Hydrodynamics Fluid’
(2021)](https://wang-mengdi.github.io/proj/thin-film-sph/), that I co-authored. I introduce a physically based rendering
model which allows point cloud simulation data representing thin film
fluids and bubbles to be rendered in a photorealistic manner. This includes simulating the optic phenomenon of thin-film interference and
rendering the resulting iridescent patterns. The key to the model lies
in the implementation of a physically based surface shader that accounts for the interference of infinitely many internally reflected rays
in its bidirectional surface scattering function. By simulating the effect of interference on rays reflected off the surface of a thin-film as a
component of a surface shader, I am able to obtain photorealistic renderings of bubbles and thin-films. This enables us to visualize complex
vortical swirls and turbulent surface flows on oscillating and deforming
surfaces in a physically accurate and visually evocative manner.

## Methodology
I developed an independent rendering and visualization methodology for thin-film and bubble simulations. These methodologies could be adapted to represent various types of simulations, ranging from point-set data to mesh-based simulations.

The visualization involves key processes:
1. Mathematical modelling of thin-film interference
2. Implementation of a physically based surface shader representing the thin-film reflectance model
3. Implementation of methods to visualize point set surfaces as physically accurate representations of thin-film fluids
4. Rendering and lighting workflows to produce evocative and accurate results

The technical contributions of these methodologies are:
1. Recreating photorealistic iridescent colours based on localized thin-film thickness distribution
2. Visualizations of dynamic point-set surfaces with a focus on geometric representation and temporal coherence
3. High quality animations visualizing the evolution of surface flows and rich colours in thin-film structures

## Videos of Results
Rendering results (included in [SIGGRAPH 2021 Trailer](https://www.youtube.com/watch?v=Ros7ZXqLbFg))
{% youtube __1VjKF-gTk  %}

## Still Results and Works in Progress
### PBRT Shader Tests
![Dragon](/dragon.png)
![Kangaroo](/kangaroo.png)
![Bubble](/material-testball.png)

### Houdini Bubble Renderings
![Render1](/Active_Render.0150.0.jpg)
![Render2](/Active_Render.0694.0.jpg)
![Render3](/H18-F5-19.png)
![Render4](/S3-IR5-SpectralOefner271.png)
![Render5](/5_square.jpg)
![Render6](/6_rt.jpg)
![Render7](/burst_teaser.jpg.png)


## Awards
### Grand Prize for Best Undergraduate Research Video 
[MAD Research: Video Competition](https://students.dartmouth.edu/ugar/news-events/highlighting-undergraduate-research/mad-research-video-competition)

