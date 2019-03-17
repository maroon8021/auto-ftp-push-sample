FROM jenkinsci/jenkins

USER root

# install jenkins plugins
COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/plugins.sh /usr/share/jenkins/plugins.txt

USER jenkins

# https://dev.classmethod.jp/tool/jenkins/jenkins-on-docker/