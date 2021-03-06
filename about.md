---
layout: page
title: About
permalink: /about/
---

I am a data, python, and open source enthusiast. I currently work on the deposits team at Live Oak Bank. 

Some of the packages I have worked on are:

### [skedm][skedm-gh]

skedm (scikit empirical dynamic modeling) is a package for performing nonlinear analysis in scikit learn's style. It can reconstruct state spaces, forecast, and see if the behavior of a system has changed.

### [skccm][skccm-gh]

skccm (scikit convergent cross mapping) implements [convergent cross mapping][ccm-wiki] in scikit learn's style. It reconstructs the state spaces and determines if one time series is influencing another time series. It implements the procedure described in [Detecting Causality in Complex Ecosystems][ccm-paper].


### [BuoyPy][buoypy-gh]

BuoyPy pulls data from the [National Data Buoy Center][ndbc], cleans it, and puts it into pandas dataframes.


[buoypy-gh]: https://github.com/nickc1/buoypy
[ndbc]: http://www.ndbc.noaa.gov/
[skedm-gh]: https://github.com/nickc1/skedm
[skccm-gh]: https://github.com/nickc1/skccm
[ccm-wiki]: https://www.wikiwand.com/en/Convergent_cross_mapping
[ccm-paper]: http://science.sciencemag.org/content/338/6106/496
