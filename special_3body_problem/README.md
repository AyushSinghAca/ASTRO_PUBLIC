# Orbital Mechanics: The Triple Body Problem – The Algol System

I learned to solve  a special case of the three-body problem, where two objects are in a close, inner orbit. Together with a third, 
more distant object, they follow an  outer orbit around the common center of mass. Such a configuration is found in the triple star system Beta Persei, 
which is also known as Algol. In this system, Algol Aa1 and Aa2 constitute an eclipsing binary with a period of less 
than three days, while this binary and a third star (designated Algol Ab) revolve around each other with a period of 680 days.

## Overview

This repository contains Python code that simulates the orbital motion of the Algol system. It calculates the initial conditions 
for the three stars based on Kepler's laws, integrates the equations of motion using the RK45 method (`solve_ivp` from SciPy), and visualizes the resulting trajectories.

## Key Features:
- Orbital Parameter Calculation: Uses the vis-viva equation and Kepler's third law to determine the semi-major axes and velocities.
- Three-Body Dynamics: Sets up the state vector for the triple system (inner binary and outer orbit) and computes gravitational interactions.
- Numerical Integration: Utilizes SciPy’s `solve_ivp` with the RK45 integrator for solving the differential equations.
- Visualization: Plots the orbits of the three stars in astronomical units (AU).

## Disclaimer  

I did not develop this code from scratch. It is based on concepts and examples from the book:  
Wolfram Schmidt & Marcel Völschow – *Numerical Python in Astronomy and Astrophysics: A Practical Guide to Astrophysical Problem Solving

If any conflicts or discrepancies arise, please refer to the book rather than relying on me. I am new to this topic and cannot guarantee the accuracy of the code.
I have tried my best to include comments for each line with AI assistance. If any confusion arises, please refer to page 145 of the book for a proper explanation.  

## Licience

Feel free to modify any sections to better suit your repository or personal preferences.

