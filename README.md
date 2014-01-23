# Hello Maven B2
This is a simplest case scenario to develop a B2 with maven.

It contains the following:
* pom.xml
* src/main/webapp/hello.jsp
* src/main/webapp/WEB-INF/web.xml
* src/main/webapp/WEB-INF/bb-manifest.xml

It leverages justplainwilly's b2deploy-task in the pom file to enable easy deployment to 
a blackboard development server.

There are three steps to deploy:

1. The Blackboard server has **[Starting Block](http://behind.blackboard.com/downloads/details.aspx?d=1669)** installed
1. The bbhost property is pointed at the correct server
1. Finally, run `mvn install antrun:run`

This project was created for the [BasicMavenB2Tutorial](https://github.com/justinwrobel/bbmd/blob/master/BasicMavenB2Tutorial.md)
