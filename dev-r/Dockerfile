FROM philcompton/dev-base
ENV BUILD_DATE 20190714

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      gcc-fortran \
      make \
      pkgconf \
      r \
    && pacman -Scc --noconfirm 

RUN Rscript -e 'install.packages("tidyverse", repos="https://cran.cnr.berkeley.edu/")'

CMD /bin/bash