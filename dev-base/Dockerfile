FROM archlinux/base
ENV BUILD_DATE 20190610
RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
      bash-completion \
      git \
      jq \
      httpie \
      lsb-release \
      subversion \
      tar \
      wget \
    && pacman -Scc --noconfirm

CMD /bin/bash