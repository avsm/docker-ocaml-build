# Autogenerated by OCaml-Dockerfile scripts
FROM centos:centos7
MAINTAINER Anil Madhavapeddy <anil@recoil.org>
RUN yum install -y sudo passwd git
RUN yum groupinstall -y "Development Tools"
RUN yum install -y ocaml ocaml-camlp4-devel ocaml-ocamldoc
RUN git config --global user.email "docker@example.com"
RUN git config --global user.name "Docker CI"