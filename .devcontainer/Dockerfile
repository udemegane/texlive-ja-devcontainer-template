FROM korosuke613/ubuntu-texlive-ja:latest

MAINTAINER Futa HIRAKOBA

RUN apt-get update && apt-get install -y \
    git \
    cpanminus \
    texlive-full \
    texlive-science \
    make \
    && apt-get clean

RUN cpanm Log::Log4perl Log::Dispatch::File YAML::Tiny File::HomeDir Unicode::GCString