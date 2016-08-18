FROM openjdk:8u102-jdk

MAINTAINER Rui Fernando Hayashi <rfhayashi@gmail.com>

# rake
RUN apt-get update && apt-get install -y rake=10.3.2-2

# leiningen
ENV LEIN_ROOT true
RUN wget -q -O /usr/bin/lein \
        https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein \
        && chmod +x /usr/bin/lein && lein upgrade 2.6.1