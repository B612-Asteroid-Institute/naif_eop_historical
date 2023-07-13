# naif_eop_historical: NAIF Historical Earth Orientation Parameters Kernel for SPICE
#### A Python package by the Asteroid Institute, a program of the B612 Foundation

[![Python 3.7+](https://img.shields.io/badge/Python-3.7%2B-blue)](https://img.shields.io/badge/Python-3.7%2B-blue)
[![PyPI version](https://img.shields.io/pypi/v/naif-eop-historical)](https://img.shields.io/pypi/v/naif-eop-historical)
[![PyPi downloads](https://img.shields.io/pypi/dm/naif-eop-historical)](https://img.shields.io/pypi/dm/naif-eop-historical)  
[![Build and Test](https://github.com/B612-Asteroid-Institute/naif_eop_historical/actions/workflows/build_test.yml/badge.svg)](https://github.com/B612-Asteroid-Institute/naif_eop_historical/actions/workflows/build_test.yml)
[![Build, Test, & Publish](https://github.com/B612-Asteroid-Institute/naif_eop_historical/actions/workflows/build_test_publish.yml/badge.svg)](https://github.com/B612-Asteroid-Institute/naif_eop_historical/actions/workflows/build_test_publish.yml)  

This package ships the Navigation and Ancillary Information Facility's high accuracy, historical Earth orientation parameters (EOP) [kernel](https://naif.jpl.nasa.gov/pub/naif/generic_kernels/pck/earth_720101_230601.bpc).

**This is not an official NAIF package**. It is an automatically generated mirror of the file so that it is
installable via `pip`. 

The current version of the file released on 2007 APR 27 spans the following times: 1972 JAN 01 00:00:42.183 - 2023 JUN 01 00:01:09.184

## Installation

The latest version of the file can be installed via pip:  
`pip install naif-eop-historical`

## Usage
```python
import spiceypy as sp
from naif_eop_historical import eop_historical

sp.furnsh(eop_historical)
```

## Acknowledgment

This project makes use of data provided and maintained by the Navigation and Ancillary Information Facility (NAIF). 

### References
[1] Acton, C.H.; "Ancillary Data Services of NASA's Navigation and Ancillary Information Facility;" Planetary and Space Science, Vol. 44, No. 1, pp. 65-70, 1996.
DOI 10.1016/0032-0633(95)00107-7  
[2] Charles Acton, Nathaniel Bachman, Boris Semenov, Edward Wright; A look toward the future in the handling of space science mission geometry; Planetary and Space Science (2017);
DOI 10.1016/j.pss.2017.02.013
