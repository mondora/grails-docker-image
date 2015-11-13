FROM java:7
RUN mkdir /usr/lib/grails
WORKDIR /usr/lib/grails
RUN wget http://dist.springframework.org.s3.amazonaws.com/release/GRAILS/grails-2.2.5.zip
RUN unzip grails-2.2.5.zip && rm grails-2.2.5.zip
ENV JAVA_HOME /usr/lib/jvm/java-7-openjdk-amd64/
ENV GRAILS_HOME /usr/lib/grails/grails-2.2.5/
ENV PATH $PATH:$GRAILS_HOME/bin
