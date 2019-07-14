FROM philcompton/dev-base
ENV BUILD_DATE 20190714

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      composer \
      php \
      php-gd \
      php-grpc \
      php-mongodb \
      php-odbc \
      php-pgsql \
      php-phpdbg \
      php-sodium \
      php-tidy \
    && pacman -Scc --noconfirm \

CMD /bin/bash