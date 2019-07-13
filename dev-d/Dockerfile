FROM philcompton/dev-base
ENV BUILD_DATE 20190713

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      dlang-dmd \
      dtools \
     && pacman -Scc --noconfirm

CMD /bin/bash