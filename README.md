# Guppy automated learning chamber

<p>
<img src="https://github.com/wyatt-toure/automated-learning-chamber-analysis/blob/main/docs/static/images/GLoW-readme-logo.svg" style="display:block; margin: 0 auto;"   width = '50%'>
</p>

This is the repository for the Guppyy Learning over Wifi (GLoW) project version 1. This project was an Honour's thesis project conducted by Beatriz Qunieche (Fall 2020/Winter 2021) in the Reader laboroatory at McGill University. The repository hosts the materials used to construct the GLoW project site at https://wyatt-toure.github.io/guppy-automated-learning-chamber/. 

We hope to imrpove GLoW in the future and make the materials as well as data collected from our pilot run of GLoW available to those who want to build something similar for their own purposes

## Summary

GLoW is a low-cost Raspberry Pi based fish tank apparatus that allows us to remotely and automatically conduct fish learning experiments. This was particularly useful given that COVID-19 restrictions meant we had extremely limited in person laboratory access. With GLoW one can conduct experiments over Wi-Fi from home. The goal of version 1 of GLoW was to get Trinidadian guppies to pair a light stimulus with a food reward. You can see an example of GLoW in action below. 

<p>
<img src="images/guppy-learning-chamber-sample-trial.gif" style="display:block; margin: 0 auto;"   width = '50%'>
</p>



## Directory structure

- `data/` contains the raw data collected from GLoW and used to conduct the analyses
- `docs/` contains the html write-up of the analyses, the GitHub pages site is built from this folder
- `images/` contains relevant images and videos of the experiment

The root directory contains R markdown files which are subsequently rendered to html outputs for the site.
