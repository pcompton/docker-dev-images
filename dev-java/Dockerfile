FROM philcompton/dev-base
ENV BUILD_DATE 20190619

RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
      jdk-openjdk \
      gradle \
      maven \
      openjdk-src \
    && pacman -Scc --noconfirm

CMD /bin/bash