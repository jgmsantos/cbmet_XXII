# Scripts para o curso de Python realizado no Congresso Brasileiro de Meteorologia em 2002 - Edição XXII

## Informações gerais sobre o curso

* Curso: Python aplicado a Meteorologia.
* Ministrante: Dr. Guilherme Martins - jgmsantos@gmail.com.
* Dia 1: 30/11/2022.
  * Duração: 2 horas (16h00-18h00).
* Dia 2: 01/12/2022.
  * Duração: 2horas (16h00-18h00).
* Local: Fundeb - Sala Urano.

## Criação do ambiente virtual
* Para criar um ambiente virtual para quem usa conda, basta digitar o comando abaixo. E para quem não usa, basta seguir para o próximo item de instalação de bibliotecas.

```conda create -n cbmet python=3.9.12```

* **Importante**: Reiniciar o computador após criar o ambiente virtual.

## Instalação de bibliotecas
```pip3 install --upgrade pip```

```pip install fastai==2.5.6```

```pip install matplotlib==3.4.3```

```pip install ipykernel```

```conda install -c conda-forge xarray dask netCDF4 bottleneck```

```pip install proplot==0.9.4```

```conda install -c conda-forge cartopy```

```pip install geopandas==0.10.2```

```pip install rasterio==1.2.10```

```pip install salem==0.3.7```

```pip install pygeos==0.12.0```

```pip install rtree==1.0.0```

```conda install -c conda-forge ncview```

## Conteúdo programático (EM CONSTRUÇÃO!!!)

* Biblioteca xarray para abrir, manipular e processar arquivos no formato NetCDF (nome do script: ```xarray.ipynb```).
* Geração de figuras.
* Criação de painel complexo para geração de figuras (nome do script: ```gridspec.ipynb```).

## Material de apoio

* [Aplicações de Python em Geociências](https://drive.google.com/file/d/15_62F9lb21XDhCsYL_YoKIuuAATNWpNw/view)
* [https://guilherme.readthedocs.io/en/latest/pages/tutoriais/python.html](https://guilherme.readthedocs.io/en/latest/pages/tutoriais/python.html)

## Rede sociais

* [Minha página pessoal](https://guilherme.readthedocs.io/en/latest)
* [Canal no Youtube](https://www.youtube.com/c/CursosLibertatem)
* [Instagram](https://www.instagram.com/cursos.libertatem)