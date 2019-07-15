FROM philcompton/dev-base
ENV BUILD_DATE 20190715

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      gcc \
      make \
      ruby \
      ruby-bundler \
      ruby-irb \
      ruby-yard \
      rubygems \
    && pacman -Scc --noconfirm 

RUN gem install rails

CMD /bin/bash