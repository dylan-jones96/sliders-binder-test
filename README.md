# sliders-binder-test

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dylan-jones96/sliders-binder-test/HEAD)

First binder configuration for displaying band structures with parameter varying sliders. 

Current state of things is that the sliders functionally work, but in an ugly way where the figure axis is redrawn every time. I don't like this, it is slow and inefficient. Surely there is a way of linking a figure's axes object to the sliders and using the set_ydata method available in matplotlib? This doesn't work with sliders (as far as I can tell) as the matplotlib figures aren't widgets, whereas bqplot figures are. 
