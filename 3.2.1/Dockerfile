FROM java:8
RUN apt-get update && apt-get install -y nano vim telnet
RUN mkdir /usr/lib/grails
WORKDIR /usr/lib/grails
RUN wget https://github.com/grails/grails-core/releases/download/v3.2.1/grails-3.2.1.zip
RUN unzip grails-3.2.1.zip && rm grails-3.2.1.zip
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64/
ENV GRAILS_HOME /usr/lib/grails/grails-3.2.1/
ENV PATH $PATH:$GRAILS_HOME/bin