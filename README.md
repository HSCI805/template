# Specifying an R environment with a runtime.txt file

Jupyter+R: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?filepath=index.ipynb)

RStudio: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=rstudio)

RShiny: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=shiny/bus-dashboard/)

Binder supports using R and RStudio, with libraries pinned to a specific
snapshot on [packagemanager.rstudio.com](https://packagemanager.rstudio.com/client/#/).

### Steps

1. Fork this repository

2. Update `runtime.txt` with newer date:  
```
r-<r-version>-<YYYY>-<MM>-<DD>
```
- Newer date: visit https://packagemanager.rstudio.com/client/# and choose a date surrounded by a solid bounding box 

3. Visit https://mybinder.org/ and enter github's URL 

