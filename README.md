# Coarse-to-fine Deformetrica

This code is an extension of the software Deformetrica.
It implements a coarse-to-fine strategy for atlas construction.

## Installation
  
    git clone https://github.com/fleurgaudfernau/Deformetrica_coarse_to_fine

Create a virtual environment:

    conda create -n deformetrica python=3.7 && source activate deformetrica

OR

    virtualenv -p python3 deformetrica && source deformetrica/bin/activate

Install the requirements inside the new environment:

    python3 -m pip install -r deformetrica_original/requirements.txt

Install developer version:

    python3 -m pip install Deformetrica_coarse_to_fine/.


## About Deformetrica


Website: [www.deformetrica.org](http://www.deformetrica.org/)

**Deformetrica** is a software for the statistical analysis of 2D and 3D shape data. It essentially computes deformations of the 2D or 3D ambient space, which, in turn, warp any object embedded in this space, whether this object is a curve, a surface, a structured or unstructured set of points, an image, or any combination of them.

_Deformetrica_ comes with three main applications:
- **registration** : estimates the best possible deformation between two sets of objects;
- **atlas construction** : estimates an average object configuration from a collection of object sets, and the deformations from this average to each sample in the collection;
- **geodesic regression** : estimates an object time-series constrained to match as closely as possible a set of observations indexed by time.

_Deformetrica_ has very little requirements about the data it can deal with. In particular, it does __not__ require point correspondence between objects!

