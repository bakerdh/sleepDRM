FROM rocker/verse:4.2.2

RUN apt-get update -qq
RUN apt-get -y install git
RUN apt-get -y install libgl1-mesa-dev 
RUN apt-get -y install libglu1-mesa-dev

RUN install2.r –error \
--deps TRUE \
rmarkdown \
bookdown \
kableExtra \
knitr \
rstatix \
osfr \
tidyr \
plyr \
dplyr \
emmeans \
Rmisc \
buildmer \
lme4 \
lmerTest \
stringr \
effects \
effectsize \
ggdist \
car \
gridExtra \
simr \
effsize \
LSAfun \
readr \
Gmisc \
glue \
htmlTable \
magrittr \
magick \
cowplot
