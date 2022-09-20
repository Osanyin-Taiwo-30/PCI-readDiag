# Instalação

Para instalar o pacote readDiag, é recomendado que o usuário prepare um ambiente do Python específico para o se uso. Para isto, o pacote fornece o arquivo `environment.yml` para a construção desse ambiente utilizando a [Distribuição Python do Anaconda](https://www.anaconda.com/products/distribution).

Alguns dos pacotes do Python necessários para a utilização do readDiag:

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

Para criar o ambiente Python para o uso do pacote readDiag, utilize o comando `conda`, disponível após a instalação do Anaconda:

```bash linenums="1"
conda env create -f environment.yml
```

!!! warning "Atenção"

    Para a instalação do pacote readDiag, é necessário que um compilador Fortran instalado no computador do usuário. Se o ambiente Python do readDiag estiver corretamente configurado, não será necessário instalar pacotes adicionais.

Para instalar o pacote do readDiag, primeiro ative o ambiente criado com o comando:

```bash linenums="1"
conda activate readDiag
```

e instale o pacote readDiag com o comando:

```bash linenums="1"
python setup.py install
```

!!! note "Nota"

    Para desinstalar o pacote readDiag (caso necessário), utilize o comando `pip uninstall gsidiag`.
