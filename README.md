# Maven

PROXY SETTINGS
--------------
settings.xml file

 <settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
                          https://maven.apache.org/xsd/settings-1.0.0.xsd">
<proxies>
    
    <proxy>      
      <active>true</active>
      <protocol>http</protocol>
      <username>628200</username>
      <password>{ZWOjTJSRBK0Hba3GRyQ+fSFeuwyB9p7V6WOQeMx+Ft4=}</password>
      <host>proxy.cognizant.com</host>
      <port>6050</port>
      <nonProxyHosts>www.google.com</nonProxyHosts>
    </proxy>
    
  </proxies>
    </settings>
    
mvn --encrypt-master-password

	{kf0fKjrBcDMHYY6xKGZx4d2GoPQhDDkmXSVQCJvYGuk=}

settings-security.xml in the ~/.m2 

	<settingsSecurity>
  	<master>{kf0fKjrBcDMHYY6xKGZx4d2GoPQhDDkmXSVQCJvYGuk=}</master>
	</settingsSecurity>



mvn --encrypt-password

	Put the generated password  in settings.xml
