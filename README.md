# scratchx-utilities
An extension for ScratchX to provide some useful utility blocks

## Utilities Provided

* noise(x): Simplex noise in 1 dimension
* noise(x,y): Simplex noise in 2 dimensions
* noise(x,y,z): Simplex noise in 3 dimensions
* noise(x,y,z,t): Simplex noise in 4 dimensions

## Credits

Includes Jonas Wagner's Simplex Noise, which itself includes Johannes Baagøe's Alea pseudo-random number generator (PRNG): https://github.com/jwagner/simplex-noise.js/

The current implementation uses a constant seed for the PRNG so the noise returned is always consistent.