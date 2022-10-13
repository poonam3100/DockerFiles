FROM ubuntu:latest

# Install basic software support
RUN apt-get update && \
    apt-get install --yes software-properties-common

# Install Java 8
RUN apt-get -y install openjdk-8-jdk wget

RUN java -version

# # Jetty/Tomcat port
# EXPOSE 8080