# Material accompanying the lecture 'Cosmological ICs and PT-informed integrators' by Oliver Hahn at Les Houches Summer School 2025 "The Dark Universe" 
This lecture was part of the 2025 Les Houches Summer School ["The Dark Universe"](https://indico.iap.fr/event/25/)

You can access a recording of the full 90min lecture (along with all other lectures) as well as the lecture slides [via indico](https://indico.iap.fr/event/25/contributions/227/)

This repository contains 
* the jupyter notebook used in the lecture, illustrating how to sample a Gaussian random field corresponding to a cosmic density field from a [CAMB](https://camb.readthedocs.io/en/latest/) power spectrum, how to generate a displacement field for first order characteristics (Zel'dovich approximation), and how to render it in 3D using PyVista
* Lecture notes in PDF format, currently in draft form (notes are submitted but not yet peer reviewed)

The notebook is meant for educational purposes. To generate high-quality cosmological initial conditions for production simulations, consider using
* [monofonIC](https://github.com/cosmo-sims/monofonIC) for up to 3LPT ICs, incl. baryons, MPI-parallel, for single resolution precision cosmology simulations
* [MUSIC](https://github.com/cosmo-sims/MUSIC2) for high-resolution zoom ICs up to 2LPT, with output for a huge range of codes
