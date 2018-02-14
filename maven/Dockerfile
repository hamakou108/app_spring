FROM maven:3.5.2-jdk-8
LABEL maintainer="hamakou108 <kosuke1602177mteitm19@gmail.com>"

# project directory
RUN mkdir -p /opt/app
WORKDIR /opt/app

# copy setting files
COPY settings.xml /usr/share/maven/conf/

# additional maven commands
#RUN mvn clean install

CMD ["/bin/bash"]
