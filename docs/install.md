# Installation

To install the readDiag package it is recomended to the user to setup a specific Python environment. For this purpose, an `environment.yml` file is provided to create the recommended environment using the [Anaconda Python distribution](https://www.anaconda.com/products/distribution).

Some of the Python packages required by the readDiag include:

* matplotlib;
* basemap;
* cartopy;
* proj4;
* pyproj;
* libgeos;
* geopandas.

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
