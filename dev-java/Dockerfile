FROM philcompton/dev-base
ENV BUILD_DATE 20190731

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      gradle \
      jdk11-openjdk \
      maven \
      openjdk11-src \
    && pacman -Scc --noconfirm

CMD /bin/bash