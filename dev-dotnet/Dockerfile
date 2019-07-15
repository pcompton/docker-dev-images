FROM philcompton/dev-base
ENV BUILD_DATE 20190715
ENV DOTNET_ROOT /opt/dotnet
ENV PATH="/opt/dotnet:${PATH}"

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      icu \
    && pacman -Scc --noconfirm

RUN mkdir -p /opt/dotnet \
    && wget https://download.visualstudio.microsoft.com/download/pr/3224f4c4-8333-4b78-b357-144f7d575ce5/ce8cb4b466bba08d7554fe0900ddc9dd/dotnet-sdk-2.2.301-linux-x64.tar.gz \
    && tar xzf dotnet-sdk-2.2.301-linux-x64.tar.gz -C $DOTNET_ROOT \
    && rm dotnet-sdk-2.2.301-linux-x64.tar.gz


CMD /bin/bash