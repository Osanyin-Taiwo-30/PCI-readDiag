# Installation

To install the readDiag package it is recommended to the user to setup a specific Python environment. For this purpose, an `environment.yml` file is provided to create the recommended environment using the [Anaconda Python distribution](https://www.anaconda.com/products/distribution).

Some of the Python packages required by the readDiag include:

* basemap;
* cartopy;
* gcc;
* geopandas;
* geos;
* gfortran;
* matplotlib;
* numpy;
* pandas;
* proj4;
* pyproj;
* python (3.7.6);
* xarray.

To create the Python environment for the readDiag package, use the `conda` command (provided by the Anaconda installer):

```bash linenums="1"
conda env create -f environment.yml
```

!!! warning "Warning"

    The installation of the readDiag package requires a Fortran compiler installed in the host machine. If the Python environment is correctly set up, there is no need to install any other packages.

In order to install the readDiag package, first activate it by issuing the command:

```bash linenums="1"
conda activate readDiag
```

and proceed to install the readDiag package with the command:

```bash linenums="1"
python setup.py install
```

!!! note "Note"

    To uninstall the readDiag package (if needed) use the command `pip uninstall gsidiag`.
