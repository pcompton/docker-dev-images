FROM philcompton/dev-base
ENV BUILD_DATE 20190601

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