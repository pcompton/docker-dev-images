FROM archlinux/base
ENV BUILD_DATE 20190713
RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      bash-completion \
      git \
      jq \
      httpie \
      lsb-release \
      tar \
      wget \
    && pacman -Scc --noconfirm

CMD /bin/bash