FROM thomasweise/texlive:latest
MAINTAINER Clemens Weissbacher <weimens@gmail.com>

RUN apt-get update && apt-get install -y \
  texlive-fonts-extra \
  latexmk \
  tree \
  && rm -rf /var/lib/apt/lists/*
