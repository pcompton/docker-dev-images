FROM philcompton/dev-java
ENV BUILD_DATE 20190715

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      nodejs-lts-dubnium \
      yarn \
    && pacman -Scc --noconfirm \
    && yarn global add --non-interactive @angular/cli

CMD /bin/bash