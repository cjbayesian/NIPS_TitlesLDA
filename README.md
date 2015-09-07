# Categorizing NIPS papers using LDA topic modeling

Trying to decide what papers you're interested in at this year's NIPS? This repo consists of an ipython notebook implementing a simple LDA topic model over paper titles.

The LDA code is adapted from Jordan Barber's blog post [Latent Dirichlet Allocation (LDA) with Python](https://rstudio-pubs-static.s3.amazonaws.com/79360_850b2a69980c4488b1db95987a24867a.html)

## Installation
*   Install [anconda](http://continuum.io/downloads) package manager

*  In the directory containing environment.yml, execute following:
```
   $ conda env create
```

*  If environment.yml gets update in git repo, remember to update the env:
```
    $ conda env update
```

*  Next activate the new conda environment: 
```
source activate nips_papers_LDA
```

*  Launch the notebook server:
```
ipython notebook
```
