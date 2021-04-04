# Tomcat-apache
$ cd /opt
$ sudo wget http://apache.YourFavoriteMirror.com/tomcat/tomcat-[#]/v[#]/apache-tomcat-[#].tar.gz
$ ls
$ sudo tar -xvzf apache-tomcat-9.0.44.tar.gz  [to exract the file]
$ sudo chmod -R 777 apache-maven-3.6.3  [giving full permistion to the floder]
$ cd apache-tomcat-9.0.44
$ cd bin [bin forlder has starting scripts]
$ sh startup.sh [to start the apache server]
$ ps -ef | grep java [to check the apache server is runing are not]
$ netstat -tupln [ To check the port number and port is runingare not]
$ sh shutdown.sh [to shutdown the server]
  
  
To bulid and deploy in tomcat
=================================
$ cd maven-web-app
$ ls
$ mvn clean install [to do bulid function]
$ cd /opt
$ ls
$ cd apache-tomcat-9.0.44
$ ls
$ cd webapps 
$ pwd 
  /opt/apache-tomcat-9.0.44/webapps  [copy the path]
$ cd 
$ cd maven-web-app
$ ls
$ cd target
$ cp posh-technologies.war  /opt/apache-tomcat-9.0.44/webapps [we are cp war file and delpoy to server]
$ ip:8080/posh-technologies [To check the application is deploy]
