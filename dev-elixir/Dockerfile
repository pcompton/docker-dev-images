FROM philcompton/dev-base
ENV BUILD_DATE 20190715
ENV ELIXIR_VERSION 1.9.0
ENV ELIXIR_HOME /opt/elixir
ENV PATH="/opt/elixir/bin:${PATH}"

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      erlang-nox \
    && pacman -Scc --noconfirm

RUN mkdir -p /opt/elixir \
    && wget https://github.com/elixir-lang/elixir/releases/download/v${ELIXIR_VERSION}/Precompiled.zip \
    && python -m zipfile -e Precompiled.zip /opt/elixir/ \
    && rm Precompiled.zip

RUN chmod a+x /opt/elixir/bin/elixir /opt/elixir/bin/elixirc /opt/elixir/bin/iex /opt/elixir/bin/mix


CMD /bin/bash