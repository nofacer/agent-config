FROM openshift/jenkins-slave-maven-centos7
USER root
ENV PATH="/opt/gradle-4.7/bin:${PATH}"


RUN curl -LOk https://services.gradle.org/distributions/gradle-4.7-bin.zip && \
    rm -rf /opt/gradle && \
    mkdir /opt/gradle && \
    unzip  -d /opt/ gradle-4.7-bin.zip
