Java-SMTP-Server
================

A simple SMTP server with a web interface.  This application is implemented using Java Servlets, embedded Derby database and JQuery and is packaged into a single jar file along with Winstone web server. The main purpose of this application is to facilitate testing of applications that sends emails without having to worry about getting valid unique email addresses for each and every user in the system.

The source code is available in Winstone.jar/embedded.war

Use the following to run the project
====================================
java -jar winstone.jar --useJasper --javaHome=$JAVA_HOME
