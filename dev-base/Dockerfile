FROM archlinux/base
ENV BUILD_DATE 20190731
RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      bash-completion \
      gawk \
      git \
      jq \
      httpie \
      lsb-release \
      tar \
      wget \
      which \
    && pacman -Scc --noconfirm

CMD /bin/bash