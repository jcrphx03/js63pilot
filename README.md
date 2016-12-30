#js63pilot
 Customizations added to new js version 6.3

Login Page 
 
1. Hide the following elements
    _Need Help Loogin In?
    _Amazon Label

Welcome Page
2.  Replace  TIBCO links and logo with:
   
    _BB logo ( bb_logo_welcome.png ) 
    _Welcome to Card Reports Center

3. Images
 Added the following BB images: 
  bb_logo_welcome.png
  favicon.png
  bb_logo.png

4. Tomcat changes
   _In favicon 
    Replace "TIBCO jaspersoft" brand name with "Blackboard Transact" name
    For this purpose modify the following property: 

    company.name="TIBCO Jaspersersoft" 
    file: /opt/tomcat8/webapps/jasperserver-pro/WEB-INF/bundles/jasperserver_messages.properties


Where are the solutions:
 File: overrides_custom.css
 It is resolving the requirements "1","2","3"

File: jasperserver_messages.properties
 It is resolving the requirement "4"
