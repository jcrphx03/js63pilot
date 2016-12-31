#js63pilot
 Customizations added to new js version 6.3

Cust#1. Login Page 
 
   Hide the following links:
    _Need Help Loogin In?
    _Amazon Label

Cust#2. Welcome Page
    Replace  TIBCO links and logo with:
   
    _BB logo ( bb_logo_welcome.png ) 
    _Welcome to Card Reports Center

Cust#3 Images
 Added the following BB images: 
  bb_logo_welcome.png
  favicon.png
  bb_logo.png


  Very Important: For favicon.png to be recognized by the system you should enter "favicon.ico" name in the "add file" form and as follow more detail
                  will be posted in Confluence:
                  Name (required): favicon.png 
                  Resource ID (required): favicon.ico  
          

Cust#4 Tomcat changes
   _In favicon 
    Replace "TIBCO jaspersoft" brand name with "Blackboard Transact" name
    For this purpose modify the following property: 

    company.name="TIBCO Jaspersersoft" 
    file: /opt/tomcat8/webapps/jasperserver-pro/WEB-INF/bundles/jasperserver_messages.properties


Where are the changes?:
 File: overrides_custom.css
 It is resolving the requirements "1","2","3"

 File: jasperserver_messages.properties
 It is resolving the requirement "4"
