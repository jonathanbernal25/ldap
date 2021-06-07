# Simple LDAP server simulating Active Directory

This is a simple LDAP server that tries to simulates an Active Directory using Apache Directory Server.

* Is based on: https://github.com/kwart/ldap-server/ 
* Is based on: http://stackoverflow.com/questions/11174835/add-memberof-attribute-to-apacheds 


## Docker

1. Build image `docker build -t jonathanbernal25/ldap .`
2. Run the image using `docker run --rm -d --name ldap -p 10389:10389 jonathanbernal25/ldap`


