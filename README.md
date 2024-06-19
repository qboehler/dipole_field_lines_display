# Magnetic dipole field lines display

## Installation

* Clone this repo

```bash
git clone git@github.com:qboehler/dipole_field_lines_display.git
```


### Installing dependencies

#### Libary for utilies functions import

The functions used in the notebooks are defined in ```utilities.ipynb``` and imported as ```from ipynb.fs.defs.utilities import *```.
This requires the following package:

``` bash
pip3 install ipynb --upgrade
```

#### Libraries for magnetic models

Install libraries for magnetic manpipulation:

``` bash
pip install mag-manip
```

#### Libraries for graphics and plotting

Install [Matplotlib and MPL_toolkits](https://matplotlib.org/stable/users/installing.html).

#### Libraries for maths and computation

Install:
* [NumPy](https://numpy.org/install/)
* [PyYAML](https://pypi.org/project/PyYAML/)
* [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
* [SciPy](https://pypi.org/project/scipy/)

#### Libraries for interval analysis

Install [PyInterval](https://pyinterval.readthedocs.io/en/latest/index.html) and the [python binding](https://www.ensta-bretagne.fr/desrochers/pyibex/docs/pyibex/installation.html) of [ibex](http://www.ibex-lib.org/).

### Installing Jupyter notebook

The Jupyter Notebook is an open source web application that you can use to create and share documents that contain live code, equations, visualizations, and text.
It is convenient to use Jupyter as an interactive python editor where you can run the code directely from a web browser and create some plots.
Install pip and the Python header files, which are used by some of Jupyter’s dependencies:

``` bash
sudo apt install python3-pip python3-dev
pip install jupyter
pip install jupyterlab
pip install ipywidgets
```

## Usage

From a terminal, cd to the root folder of this repository and launch jupyter notebook. This will open a webbrowser window.

``` bash
jupyter notebook
```
