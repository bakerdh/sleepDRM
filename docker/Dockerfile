FROM rocker/verse:4.2.2

RUN apt-get update -qq
RUN apt-get -y install git
RUN apt-get install postgresql postgresql-contrib

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
LSAfun \
simr \
effsize \
readr
