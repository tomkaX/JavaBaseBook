# Introduction

Plan

**https://docs.google.com/a/ciklum.com/document/d/1JMkwGuSpJem-zgIHJv4ei6ETJWOB9UdUkn7AGNXWcV4/edit?usp=sharing**

 file file serves as your book's preface, a great place to describe your book's content and ideas.

 INSTALL OPEN SOURCE JAVA

Installing the open source implementation of JAVA 7 can’t be easier than issuing the following command:

## apt-get install openjdk-7-jdk
INSTALL ORACLE JAVA

The best and recommended way to install Oracle JAVA is to use a PPA and install JAVA using apt as in:

## apt-get install software-properties-common
## add-apt-repository ppa:webupd8team/java
## apt-get update
## apt-get install oracle-java8-installer
## apt-get install oracle-java8-set-default
VERIFY JAVA INSTALLATION

To verify if JAVA has been successfully installed and set-up, run the following command:

## java -versionINSTALL GVM
Installing GVM (Grails/Groovy environment) is done by their automatic shell script installer. You need curl to download and run the script, so run the following commands:

## apt-get install curl
## curl -s get.gvmtool.net | bash
SET-UP TEST GRAILS PROJECT
## mkdir /projects
## grails create-app /projects/test-project
## cd /projects/test-project
## grails run-appOnce the Grails application is deployed, you can access it at http://SERVER_IP:8080/projects/test-project . To learn more about Grails, refer to their official documentation at http://grails.org/doc/latest/


