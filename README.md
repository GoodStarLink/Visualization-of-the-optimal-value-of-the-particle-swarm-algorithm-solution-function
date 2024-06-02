# Particle Swarm Optimization (PSO) Visualization

This project visualizes the Particle Swarm Optimization (PSO) algorithm on various benchmark functions. The visualization includes both static plots and animations showing the particles' movement towards the global optimum.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Benchmark Functions](#benchmark-functions)
- [PSO Parameters](#pso-parameters)
- [Visualization](#visualization)
- [References](#references)

## Introduction

Particle Swarm Optimization (PSO) is a popular optimization algorithm inspired by the social behavior of birds flocking or fish schooling. This project provides a visual representation of how PSO converges to the global optimum of various benchmark functions.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- numpy
- matplotlib

You can install the required libraries using pip:
```bash

pip install numpy matplotlib

## Usage
Clone the repository:
bash
复制代码
git clone https://github.com/yourusername/PSO-Visualization.git
Navigate to the project directory:
bash
复制代码
cd PSO-Visualization
Run the script:
bash
复制代码
python pso_visualization.py
Benchmark Functions
The project supports multiple benchmark functions to test the PSO algorithm:

Rosenbrock
Rastgrin
Ackley
Sphere
Beale
Goldstein-Price
Booth
Bukin
Matyas
Levi
Himmelblau
Three hump camel
Easom
Cross in tray
Egg holder
McCormick
Schaffer
Stiblinski-tag
Salomon
Objective
Parabolic
You can select any of these functions by passing the function name to the create_benchmark function.

PSO Parameters
The PSO algorithm parameters are initialized as follows:

c1 (cognitive coefficient): 0.8
c2 (social coefficient): 0.8
w (inertia weight): 0.6
Number of particles: 50
These parameters can be adjusted to observe different behaviors of the PSO algorithm.

Visualization
Static Plot
The script generates a static plot showing the benchmark function's contour map along with the particles' positions and the global optimum.

Animation
The animation shows the movement of particles over iterations, illustrating how they converge to the global optimum. To view the animation, run the script in a Jupyter notebook or save it as an HTML file.

python
复制代码
from IPython.display import HTML
HTML(anim.to_html5_video())