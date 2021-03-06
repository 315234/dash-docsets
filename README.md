# Dash docsets for scientific Python

Provides docsets for the [Dash](http://kapeli.com/dash) and [Zeal](http://zealdocs.org/) documentation browsers, for stable builds of the following scientific Python packages:

* [IPython](http://ipython.org/ipython-doc/stable/)
* [NumPy](http://docs.scipy.org/doc/numpy/)
* [SciPy](http://docs.scipy.org/doc/scipy/reference/)
* [pandas](http://pandas.pydata.org/pandas-docs/stable/)
* [statsmodels](http://statsmodels.sourceforge.net/stable/)
* [seaborn](http://stanford.edu/~mwaskom/software/seaborn/)

All docsets are set to use the Python language family and are added under the `python:` keyword by default. The scripts used to build the docsets are included.

## Installation in Dash

Add any or all of the following feeds to Dash:

* IPython: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/ipython.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/ipython.xml)
* NumPy: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/numpy.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/numpy.xml)
* SciPy: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/scipy.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/scipy.xml)
* pandas: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/pandas.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/pandas.xml)
* statsmodels: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/statsmodels.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/statsmodels.xml)
* seaborn: [https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/seaborn.xml](https://raw.github.com/sjpfenninger/dash-docsets/master/feeds/seaborn.xml)

## Building the docsets

`make fetch` downloads the documentation from the websites of these packages, `make build` builds docsets with minimal additional processing (see `build-docset.sh`).

[doc2dash](https://github.com/hynek/doc2dash) is required to build the docsets.
