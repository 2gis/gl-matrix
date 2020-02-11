glMatrix [![Build Status](https://travis-ci.org/2gis/gl-matrix.svg?branch=master)](https://travis-ci.org/2gis/gl-matrix)
=======================

Javascript has evolved into a language capable of handling realtime 3D graphics, 
via WebGL, and computationally intensive tasks such as physics simulations.
These types of applications demand high performance vector and matrix math,
which is something that Javascript doesn't provide by default.
glMatrix to the rescue!

glMatrix is designed to perform vector and matrix operations stupidly fast! By
hand-tuning each function for maximum performance and encouraging efficient
usage patterns through API conventions, glMatrix will help you get the most out
of your browsers Javascript engine.

Learn More
----------------------
For documentation, news, tutorials, and more visit the [glMatrix Homepage](http://glmatrix.net/)

Contributing
----------------------
Contributions are welcome! Please provide unit tests for new functionality. (See TESTING.md for details)

### Release

`npm run build && npm version patch && git push --follow-tags && npm run pub`
