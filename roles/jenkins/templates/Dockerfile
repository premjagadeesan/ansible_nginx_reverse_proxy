FROM jenkins/jenkins:2.59
COPY executors.groovy /usr/share/jenkins/ref/init.groovy.d/executors.groovy
ENV JAVA_OPTS=-Djenkins.install.runSetupWizard=false
ENV JENKINS_OPTS --prefix=/{{ app_name }}/{{ tool_name }}
