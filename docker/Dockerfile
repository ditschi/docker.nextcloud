ARG baseImage=nextcloud

FROM $baseImage as nexttcloud-plus

RUN apt-get update \
    && apt-get install -y \
      make \
      ocrmypdf \
      tesseract-ocr-eng \
      tesseract-ocr-deu \
      libreoffice \
      python3 \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
