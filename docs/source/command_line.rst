.. _command:

====================
 Command line tools
====================


image_correct.py
================

The 'image_correct' script is a general purpose tool that utilizes
topographic, BRDF and wavelength resampling fuctions to modify/correct
an image.

Configuration file
------------------

Image correction options are specified using a JSON file. Example
configuration files can be found in the github repository. We
have also created a script to automatically generates a JSON
configuration file.



trait_estimate.py
=================

The 'trait_estimate.py' script is a tool to generate maps of canopy
foliar traits given a set of model parameters. Currently only PLSR
models are supported, however support for other statistical modeling
frameworks like Gaussian process regression is currently under
development.



