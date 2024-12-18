# PanDEM
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

[Documentation here](https://scigem.github.io/pandem/), or compile it yourself following the details below.

## Installation
This package can then be installed via `pip install pandem`. If installing from github, try cloning and then running:
```
pip install -e .
```
If you make any changes to the source code, re-run those two lines to have your changes reflected in your installed package.

## Usage

If you are interested in converting a dataset from one DEM file format to antoher, you can use the installed script `pandem`, like so:

```
pandem <path_to_source_file> <path_to_output_file>
```

We support the following file formats:
 - `.data` ([MercuryDPM](https://mercurydpm.org/))
 - `.csv` ([NDDEM](https://github.com/franzzzzzzzz/NDDEM/))
 - `.dump` ([LIGGGHTS](https://www.cfdem.com/media/DEM/docu/liggghts.html))
 <!-- - `.bz2` ([YADE](https://yade-dem.org/doc/introduction.html#saving-and-loading)) -->
 <!-- - `.vtk` ([LIGGGHTS](https://www.cfdem.com/media/DEM/docu/liggghts.html)) -->

## Contributing

Something not working? Want to add your own file formats? Please consider making a pull request with changes. Otherwise please use the Issues tracker above.

## Documentation

We use `sphinx` to manage the docs. Update documentation with:
```
cd docs
make html
```
Once these are built, you can commit and push the changes to github to have them refreshed on github pages. You can also view them locally.
