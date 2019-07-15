FROM archlinux/base
ENV BUILD_DATE 20190715
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
      which \
    && pacman -Scc --noconfirm

CMD /bin/bash