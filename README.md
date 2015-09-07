# Categorizing NIPS papers using LDA topic modeling

Trying to decide what papers you're interested in at this year's NIPS? This repo consists of an ipython notebook implementing a simple LDA topic model over paper titles.

The LDA code is adapted from Jordan Barber's blog post [Latent Dirichlet Allocation (LDA) with Python](https://rstudio-pubs-static.s3.amazonaws.com/79360_850b2a69980c4488b1db95987a24867a.html)

## Installation
1. Install [anconda](http://continuum.io/downloads) package manager

2. In the directory containing environment.yml, execute following:
```
   $ conda env create
```

3. If environment.yml gets update in git repo, remember to update the env:
```
    $ conda env update
```

4. Next activate the new conda environment: 
```
source activate nips_papers_LDA
```

5. Launch the notebook server:
```
ipython notebook
```
