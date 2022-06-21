# monklab.misc
Collection of miscellaneous functions for Monklab projects

# Installation

install.packages('remotes')

remotes::install_github('seonjoo/monklab.misc@master')

# Glucocorticoid exposure score calculation

library(monklab.misc)

data(testdata)

glucocorticoid_exposure(testdata)
