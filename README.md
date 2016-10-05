# Current Build Status

Linux, OSX: [![Build
Status](https://travis-ci.org/csdms/hydrotrend-recipe.svg?branch=master)](https://travis-ci.org/csdms-stack/permamodel-recipe)

# About permamodel

Home: http://csdms.colorado.edu/wiki/Model:HydroTrend

Package license: MIT

Summary: Basin filling stratigraphic model

# Installing permamodel

To install permamodel from the csdms channel with `conda`:
```bash
$ conda config --add channels conda-forge
$ conda config --add channels csdms
```

Once these channels have been activated:
```bash
$ conda install permamodel
```

It is possible to list all of the versions of permamodel available on your
platform with:

```
$ conda search permamodel --channel csdms
```
