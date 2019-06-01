FROM philcompton/dev-base
ENV BUILD_DATE 20190601

RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
      mit-scheme \
     && pacman -Scc --noconfirm

CMD /bin/bash