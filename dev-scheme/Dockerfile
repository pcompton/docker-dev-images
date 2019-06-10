FROM philcompton/dev-base
ENV BUILD_DATE 20190610

RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
      mit-scheme \
     && pacman -Scc --noconfirm

CMD /bin/bash