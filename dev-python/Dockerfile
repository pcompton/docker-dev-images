FROM philcompton/dev-base
ENV BUILD_DATE 20190715

RUN pacman -Syu --noconfirm && pacman -S --noconfirm \
      jupyter \
      python-beautifulsoup4 \
      python-html5lib \
      python-ipykernel \
      python-matplotlib \
      python-mock \
      python-numpy \
      python-openpyxl \
      python-pandas \
      python-pandas-datareader \
      python-pillow \
      python-pip \
      python-pypdf2 \
      python-pytest \
      python-requests \
      python-scikit-learn \
      python-scipy \
      python-seaborn \
      python-selenium \
      python-send2trash \
      python-statsmodels \
    && pacman -Scc --noconfirm

CMD /bin/bash