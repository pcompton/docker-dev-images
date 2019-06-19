FROM philcompton/dev-base
ENV BUILD_DATE 20190619
ENV CC clang
ENV CXX clang++

RUN pacman -Syu --noconfirm \
    && pacman -S --noconfirm \
      clang \
      cmake \
      cppunit \
      lldb \
      llvm \
      valgrind \
    && pacman -Scc --noconfirm

CMD /bin/bash