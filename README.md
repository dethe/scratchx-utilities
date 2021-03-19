# scratchx-utilities
An extension for ScratchX to provide some useful utility blocks

Try it out: <a href="http://scratchx.org/?url=https://dethe.github.io/scratchx-utilities/utility.js">Launch ScratchX</a>

## Utilities Provided

* noise(x): Simplex noise in 1 dimension
* noise(x,y): Simplex noise in 2 dimensions
* noise(x,y,z): Simplex noise in 3 dimensions
* noise(x,y,z,t): Simplex noise in 4 dimensions
* true: A boolean that is always true
* false: A boolean that is always false
* -x: A reporter for unary negation

## Credits

Includes Jonas Wagner's Simplex Noise, which itself includes Johannes Baagøe's Alea pseudo-random number generator (PRNG): https://github.com/jwagner/simplex-noise.js/

The current implementation uses a constant seed for the PRNG so the noise returned is always consistent.