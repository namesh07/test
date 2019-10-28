FROM centos:7.2.1511
RUN yum -y install \
  java-1.7.0-openjdk \
  jenkins
EXPOSE 8080
EXPOSE 8080
CMD ["java", "-jar", "/usr/lib/jenkins/jenkins.war"]
