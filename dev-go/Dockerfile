FROM philcompton/dev-base
ENV BUILD_DATE 20190715

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      go \
      go-tools \
    && pacman -Scc --noconfirm

CMD /bin/bash