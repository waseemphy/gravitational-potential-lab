# Gravitational Potential Lab

An interactive A-level physics simulation.

Adjust two point masses and their separation to explore gravitational potential along the line through them. Compare the individual potentials with their sum, and locate the point where the gravitational field is zero.

## Use

Open `index.html` in a browser. The simulation is self-contained and can also be hosted using GitHub Pages.

## Physics model

- The masses are point masses at positions x = 0 and x = d.
- Potential is measured relative to zero at infinity.
- The combined potential is the sum of the two negative individual potentials: phi = -G M1 / r1 - G M2 / r2.
- Between the masses, the potential has a maximum where the net gravitational field is zero. The potential there is still negative.
- At each point mass, the potential tends to negative infinity. The graph clips those tails.
- Axes rescale when parameters change. Masses are in units of 10^24 kg, positions in 10^6 m, and potential in MJ/kg.

## GitHub Pages

In Settings > Pages, choose **Deploy from a branch**, then **main** and **/(root)**. Save.

## Third-party software

The self-contained page includes D3.js 7.9.0, copyright 2010–2023 Mike Bostock, under the ISC license. Its copyright notice is retained in the bundled script.
