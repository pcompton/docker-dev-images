FROM philcompton/dev-base
ENV BUILD_DATE 20190731
ENV CC gcc
ENV CXX g++

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      cmake \
      cppunit \
      gcc \
      gdb \
      make \
      valgrind \
    && pacman -Scc --noconfirm

CMD /bin/bash