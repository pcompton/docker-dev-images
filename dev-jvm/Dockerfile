FROM philcompton/dev-base
ENV BUILD_DATE 20190712

RUN apt update && apt upgrade -y && apt install -y \
      clojure \
      gradle \
      gradle-completion \
      maven \
      openjdk-11-jdk-headless \
      openjdk-11-source \
      scala \
    && rm -rf /var/lib/apt/lists/*

CMD /bin/bash