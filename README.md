This is supplemental material for the paper "Aspects of the normal state resistivity of cuprate superconductors Bi2201 and Tl2201". It includes data and three Jupyter notebooks to read the data for Tl2201 Model A, Tl2201 Model B and Bi2201. Data can be placed in the same folder as the programs for import.

The frequency we used to make this data ranges 2^12 points across a relatively wide domain, omega=+-50. This is necessary for convergence, as at this system size there is significant pileup on the tails for narrower domains. However, the bulk of the spectral weight is concentrated in a relatively small region. We provide data that was fitted across the 43 points in the range omega=+-0.5127. Though this may seem too small you can see in the provided notebooks that this still retrieves a resistivity value very similar to the results in our paper.

The spectral data in our range in omega was fitted to a set of component polynomials, the coefficients of which are stored in the provided files. The Jupyter notebooks retrieve the coefficients and then use them to reconstruct our data. A simple interpolation is also provided at the end to extend our resistivity data to other densities. 

We have also added Mathematica notebooks containing just the resistivity data plotted in our paper.

We have now also included results for LSCO and BSLCO, materials studied in the prior paper "Aspects of the normal state resistivity of cuprate superconductors". These are included here to give the community a complete set of ECFL results for all the single layer compounds we study in one convenient location.

Papers:

https://doi.org/10.48550/arXiv.2502.00293

https://doi.org/10.48550/arXiv.1911.09119
