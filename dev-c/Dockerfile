FROM philcompton/dev-base
ENV BUILD_DATE 20190713
ENV CC clang
ENV CXX clang++

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      clang \
      cmake \
      cppunit \
      gdb \
      lldb \
      llvm \
      make \
      valgrind \
    && pacman -Scc --noconfirm

CMD /bin/bash