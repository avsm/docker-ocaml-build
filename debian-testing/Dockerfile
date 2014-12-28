FROM debian:testing
MAINTAINER Anil Madhavapeddy <anil@recoil.org>
RUN apt-get -y update
RUN apt-get -y install sudo pkg-config git build-essential m4 software-properties-common aspcud unzip curl libx11-dev
RUN git config --global user.email "docker@example.com"
RUN git config --global user.name "Docker CI"
RUN apt-get -y install ocaml ocaml-native-compilers camlp4-extra