# Description

The idea of this project is to be able to easily draw genetic circuit diagrams in Ti*k*Z.
Something like `\circuit{PCT}` will draw a promoter, a coding sequence, and a terminator.

Compared to dnaplotlib, this library will focus on freeform drawing of arbitrary shapes and circuits.
You'll also get all the power of LaTeX and Ti*k*Z.
In the way that dnaplotlib can align genetic components with features in a plot in figure coordinates, you could use pgfplots in conjuction with the Ti*k*Z drawings.

For now, all that is in this repository is a PGF/Ti*k*Z library that adds a custom bent arrow node shape to use as a promoter.
