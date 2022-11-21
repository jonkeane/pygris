## pygris

__pygris__ is a Python package to help users access US Census Bureau TIGER/Line and cartographic boundary shapefiles and load them into Python as GeoDataFrames.  The goal of the package is to make it simple to access US Census geographic data; data can be acquired with a single function for a given geography (e.g. `tracts()` for Census tracts) along with a few options.  

The package is a general port of the [R __tigris__ package](https://github.com/walkerke/tigris) with a few modifications.  The framework of and philosophy behind the __tigris__ package is covered in [Chapter 5 of my book, _Analyzing US Census Data: Methods, Maps and Models in R_](https://walker-data.com/census-r/census-geographic-data-and-applications-in-r.html).  

__pygris__ has not yet been published for installation from the Python Package Index or with `conda`.  For now, install from GitHub with the following command:

```bash
pip install git+git://github.com/walkerke/pygris.git
```

Read the following articles for more information on how to use the package:

* [Basic usage of pygris](https://walker-data.com/pygris/01-basic-usage)
* [Working with geometries in pygris](https://walker-data.com/pygris/02-geometries)
* [Data utilities in pygris](https://walker-data.com/pygris/03-data-utilities)
* [Geocoding and custom filters in pygris](https://walker-data.com/pygris/04-geocoding)
