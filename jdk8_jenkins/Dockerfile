FROM openjdk:8u102-jdk

MAINTAINER Rui Fernando Hayashi <rfhayashi@gmail.com>

# rake
RUN apt-get update && apt-get install -y rake=10.3.2-2

# add user jenkins
RUN useradd jenkins --shell /bin/bash -d /var/jenkins_home 

# leiningen
RUN wget -q -O /usr/bin/lein \
        https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein \
        && chmod +x /usr/bin/lein

USER jenkins
