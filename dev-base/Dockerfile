FROM archlinux/base
ENV BUILD_DATE 20190714
RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      bash-completion \
      gawk \
      git \
      jq \
      httpie \
      lsb-release \
      sed \
      tar \
      wget \
    && pacman -Scc --noconfirm

CMD /bin/bash