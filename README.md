[![Build Status](https://travis-ci.org/dmenne/dmisc2.svg?branch=master)](https://travis-ci.org/dmenne/dmisc2)
[![Coverage Status](https://coveralls.io/repos/dmenne/dmisc2/badge.svg?branch=master&service=github)](https://coveralls.io/github/dmenne/dmisc2?branch=master)


Dmisc2
===========================================

To install on R:

devtools::install_github("dmenne/dmisc2")


Dieter Menne   
Menne Biomed Consulting Tübingen, Germany    
http://www.menne-biomed.de   

dieter.menne@menne-biomed.de 

Auxillary functions, some from Stack Exchange and r-help postings.
For some of these functions, better alternatives are meanwhile available.

* Construct contrasts in Excel files (not tested on travis); quite useful if you want nicely formatted contrast tables, but only tested on Windows.
* ggkm: Kaplan-Meier with ggplot2 was removed; use survMisc/autoplot.survfit instead
* Kruschke Highest Density. Many alternatives available.
* Pair plots splom type with categorical (http://biostatmatt.com/archives/2398). Quite nice for a first look.
* DM's default lattice settings (the function I use most frequently)
* lattice panel with paging ([Gabor Grothendiek](http://stackoverflow.com/questions/9654244/multipage-lattice-panel-arrangement)). Still the only game in town to distribute many panels on several pages. There is no equivalent plot in ggplot2. 

