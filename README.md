These materials are a computationally reproducible version of the paper:

Mak, O'Hagan, Horner & Gaskell (2023). A registered report testing the effect of sleep on Deese-Roediger-McDermott false memory: greater lure and veridical recall but fewer intrusions after sleep. Royal Society Open Science, 10: 220595. https://doi.org/10.1098/rsos.220595

The file manuscript.Rmd is an R markdown file that will perform all analyses and table creation, and produce a pdf version of the manuscript.

The full repository can be downloaded (cloned), and contains all the required data files. 
However if any data files are missing the code will attempt to download them from the OSF repository for this project: https://osf.io/9pdyf/

The 'docker' directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. In addition, the Docker environment is set up to run automatically on a remote server via Github Actions, each time a change is made (i.e. on a 'commit' to the repo). The output document is then posted back to the main repository (manuscript.pdf). If you want to make changes to the analysis and have these build automatically, you can fork the repository into your own account.

Production of the reproducible version of this manuscript was supported by an Enhancing Research Culture award from [Research England](https://www.ukri.org/councils/research-england/).

![autobuild](https://github.com/bakerdh/sleepDRM/workflows/autobuild/badge.svg)
