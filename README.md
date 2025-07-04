[![Build and Push Docker Image](https://github.com/jdeinlein/Gaussian_Splatting/actions/workflows/docker-publish.yml/badge.svg?branch=main)](https://github.com/jdeinlein/Gaussian_Splatting/actions/workflows/docker-publish.yml)

# Containerized automatic Gaussian Splatting

This repository contains the docker based pipeline for Gaussian Splatting. The pipeline is based on [COLMAP](https://colmap.github.io/) and Arthur Brussee's  [brush](https://github.com/ArthurBrussee/brush). 

## System requirements

- NVIDIA GPU with CUDA support (Driver Version 470.57.02 or higher) for CUDA accelerated reconstruction and splatting **or**
- AMD/Intel dedicated GPU for accelerated splatting only 
- For macOS: Please follow the instructions in the Installation section to install the necessary dependencies for running GPU accelerated docker containers in Podman
- < 10 GB of free disk space for the docker image
- < 8 GB of VRAM recommended

## Visualization

To view the files generated by the container you need a viewer that supports Gaussian Splatting. We recommend [Supersplat](https://superspl.at/editor).
