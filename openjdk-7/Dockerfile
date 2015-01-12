FROM inclusivedesign/centos:7

ENV JAVA_VERSION 1.7.0

RUN yum -y install java-${JAVA_VERSION}-openjdk-headless \
 && yum clean all

ENV JAVA_HOME /usr/lib/jvm/jre

CMD ["/bin/bash"]
