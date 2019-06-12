FROM haskell:8.6.5
MAINTAINER Akihito KIRISAKI

RUN apt update && apt install -y texlive-full
RUN stack --resolver lts-13.24 setup --system-ghc
RUN stack install pandoc --system-ghc
