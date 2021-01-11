# pgplot_mac

This repository comprises all the files that are modified or added in order for the
PGPLOT library to compile on macOS Big Sur 11.1.

This is my "reverse engineered" version based on Homebrew python.rb formula. Unbeknown
to me, Homebrew withdrew the formula form repository and `brew install pgplot` does not work
anymore. At least not for me. Another advantage is the creation of dynamic libraries during 
compilation.

In order to build it successfully you need to follow most of the recommendations from
original PGPLOT page (https://sites.astro.caltech.edu/~tjp/pgplot) and have all the 
standard libraries installed using Homebrew (e.g. GNU gcc, libpng etc.).
