FROM --platform=linux/amd64 maven:3.8.6-jdk-8-slim
RUN rm -fr /usr/local/openjdk-8
COPY jdk-8/ /usr/local/jdk-8/
ENV JAVA_HOME=/usr/local/jdk-8 \
    JAVA_VERSION=8u411 \
    PATH=/usr/local/jdk-8/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
