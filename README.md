# Secu_Dev_2

# POC CVE-2017-12615
POC Exploit for Apache Tomcat 7.0.0 to 7.0.79 running on Windows; CVE-2017-12615 PUT JSP vulnerability.

# Description:
By design, you are not allowed to upload JSP files via the PUT method on the Apache Tomcat servers. This is likely a security measure to prevent an attacker from uploading a JSP shell and gaining remote code execution on the server. However, due to the insufficient checks, an attacker could gain remote code execution on 7.0.{0 to 79} Tomcat servers that has enabled PUT by requesting PUT method on the Tomcat server using a specially crafted HTTP request.

# The use of Vagrantfile : 

after installing the VagrantFile : start with 

vagrant init NaoualiSeif/Seif 
vagrant up
