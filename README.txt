Cure Compass - Readme - Team 4


Deployable war: CureCompassWeb.war
Target runtime: Apache Tomcat 8
Browser: Google Chrome


Deployment procedure:
1. Download and unzip Apache Tomcat 8 onto your local machine
2. Download the CureCompassWeb.war
3. Place the war file the apache-tomcat-8.0/webapps/ folder
4. Navigate to apache-tomcat-8.0/bin/ and run the startup.bat (Assuming port 8080)
5. Open the browser and navigate to localhost:8080/CureCompassWeb/HospitalSearch
6. Name and email are optional fields and currently do not have a purpose


Code:

1. The core SPARQL funtionalities are handled in the RDFDataAccess class
2. The project is built using basic Servlet and JSP framework
3. The SPARQL is part of the CureCompass Java project, and is included under CureCompassWeb Web Project as a .jar file.
3. We have included a deployable war file as well as the two projects seperately inorder to allow easy access to code viewing.

