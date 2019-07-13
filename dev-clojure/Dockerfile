FROM philcompton/dev-java
ENV BUILD_DATE 20190713
ENV PATH="/opt/lein:${PATH}"

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      clojure \
    && pacman -Scc --noconfirm 

RUN mkdir -p /opt/lein \
    &&  curl -o /opt/lein/lein https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein \
    && chmod a+x /opt/lein/lein \
    && lein 
    

CMD /bin/bash