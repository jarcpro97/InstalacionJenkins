# InstalacionJenkins


Instalacion Jenkins en Windows

1. Instalar docker
2. Abrir powershell
3. ejecutar docker --version
6. Ejecutar docker run -p 8080:8080 -p 50000:50000 --restart always -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11

Reference

https://www.youtube.com/watch?v=f9qyXUhdyUo


Instalacion Jenkins con chrome en Windows

1. Instalar docker
2. Abrir powershell
3. ejecutar docker --version
6. Ejecutar docker run -p 8080:8080 -p 50000:50000 --restart always -v jenkins_home:/var/jenkins_home jarcpro97/jenkinschrome
