## Setting an python environment

### The easy way

Download and install [spyder](https://pythonhosted.org/spyder/). It is a bundled python environment with all the major scientific computing packages that are going to be used.

### The nerd way

`virtualenv` is python package that allows you to install other packages in contained user spaces and making it easy to have different versions of packages for different projects. It is also super useful when your want to check your code against different versions of python (2.7 and 3) are looking for unit testing platforms and easy deployements on distant web servers.

```
$ sudo easy_install pip
$ pip install virtualenv
```

Create an env and get into it:

```
$ mkdir env
$ virtualenv env/py
$ source env/py/bin/activate
```

If you want to get out of an environment, just type:

```
(py)$ deactivate
```

### Install the necessary packages

- [networkx](https://networkx.github.io/) is a library to model, visualize and perform statistics over graphs. Syntax is pretty neat and performance are good over large grahs.
- [pandas](http://pandas.pydata.org/) manipulate series and dataframes.
- [matplotlib](http://matplotlib.org/) nerd way to plot stuffs but also the more flexible.
- [seaborn](http://stanford.edu/~mwaskom/software/seaborn/) automatically tweak your plotting with good color palettes and various visualizations.
- [ipython notebook/jupyter](http://jupyter.org/) interactive literate programming for python (but also works with julia, matlab, octave and R). Make it easy to publish code and finding by uploading it on github repos.

```
(py)$ pip install networkx pandas matplotlib seaborn ipython[notebook]
```

[ ] check how to do it with spyder environment

### Start ipython notebook

The following command should open a ipython webserver in the current folder

```
(py)$ ipython notebook
```

## Other tools

- [gephi](https://gephi.org/)

## Tutorials

- [Basics of graph modelling with python](https://github.com/taniki/workshop-graphmodels-python/blob/master/Basics of graph modelling.ipynb)
- [Signed graphs](https://github.com/taniki/workshop-graphmodels-python/blob/master/Signed graphs.ipynb)

## models

- model 4
- model 6

## datasets

- gdelt http://gdeltproject.org/#downloading http://gdeltproject.org/data.html#rawdatafiles
  - http://data.gdeltproject.org/events/2001.zip

http://gdeltproject.org/data/lookups/CSV.header.historical.txt
