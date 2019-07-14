FROM philcompton/dev-base
ENV BUILD_DATE 20190714

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      nodejs-lts-dubnium \
      yarn \
    && pacman -Scc --noconfirm \
    && yarn global add --non-interactive @angular/cli

CMD /bin/bash