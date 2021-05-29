# Physically Based Rendering Techniques to Visualize Thin-Film Smoothed Particle Hydrodynamics Fluid Simulations
<img src="./images/equation-1.gif" style="display: block; margin: auto;" />

## Papers
- *research paper:* [Thin-Film Smoothed Particle Hydrodynamics Fluid](https://cs.dartmouth.edu/~bozhu/papers/sph_bubble.pdf)
- *undergraduate thesis paper:* [Physically Based Rendering Techniques to Visualize Thin-Film Smoothed Particle Hydrodynamics Fluid Simulations]()


## Abstract

This thesis introduces a methodology and workflow I developed to
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

## Still Results and Works in Progress
### PBRT

### Houdini

## Videos
{% include youtubePlayer.html id=__1VjKF-gTk %}
{% include youtubePlayer.html id=qjxJN36QFb4 %}
{% include youtubePlayer.html id=s5fE-3E_KeY %}

## Awards

### Grand Prize for Best Undergraduate Research Video 
[MAD Research: Video Competition](https://students.dartmouth.edu/ugar/news-events/highlighting-undergraduate-research/mad-research-video-competition)
{% include youtubePlayer.html id=ncq-aHAacBM %}
