﻿# notebooks

A collection of jupyter notebooks I have used to analyze particular problems, this is all generalized and anonymyzed from any source data I used.

## How to run general diagnostic tarbal analysis

* drop the analysis-general.ipynb into an opscenter diagnostic tarball folder
* place any ttops you want in there as well ideally in a given node folder
* python3 -m venv venv
* source venv/bin/activate
* pip install matplotlib pandas jupyter
* ./venv/bin/jupyter-notebook ./analysis-general.ipynb
* open up link and click on the double >>

you may have to edit one thing the threshold for slow queries is usually to high and the thing bombs.. been meaning to fix it but life is busy atm
