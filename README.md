# eap
 unzip jboss-eap-7.0.0.zip
 yum groupinstall jboss-eap7
 java -jar jboss-eap-7.0.0-installer.jar
 java -jar jboss-eap-7.0.0-installer.jar filename.xml
 
For a standalone server:

$ ${JBOSS_HOME}/bin/standalone.sh

For a managed domain host controller (which will be the master):

$ ${JBOSS_HOME}/bin/domain.sh

The main folders are described by the following bullets:

bin: Contains scripts used for starting EAP in managed domain and standalone server, start the management CLI and other utility functions for developers.

domain: Contains configuration and data files for running EAP in a managed domain

standalone: Contains the configuration and data files for running EAP standalone server.

modules: Contains most of the code that implement JEE services in EAP.

http://localhost:8080
