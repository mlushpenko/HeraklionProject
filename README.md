##HeraklionProject
================

Project about wine production: 2 business processes, 10 web services, 1 GUI

##FOR TESTING:

* Install Glassfish4 server (default port 8080). Deploy all war files on Glassfish.
 
* Install apache tomcat7 server. In server.xml change port to 9090. 
* Deploy apache ode.war on tomcat from here (http://ode.apache.org/getting-ode.html get war distribution)
* Go to localhost:9090/ode/deployment.html, enter some name for business process and upload GrapeOrder_business_process.zip.
* Repeat the same for WineOrder_business_process.zip.

* Start both servers and go to localhost:8080/WineProduction/Heraklion



##FOR MYSELF

* Go to koding.com and start terminal for vm-0.mlushpenko.kd.io virtual machine. 
* Type: sudo service tomcat7 start (password is the same as for you account)
* Type: cd glassfish4/glassfish/bin
* Type: ./asadmin start-domain
* Go to http://vm-0.mlushpenko.kd.io:8080/WineProduction/Heraklion
