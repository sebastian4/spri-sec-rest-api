spri-sec-rest-api
=================

project show spring security with rest api

links
-----

http://malalanayake.wordpress.com/2014/06/27/spring-security-on-rest-api/
http://projects.spring.io/spring-security/

curl egs
--------

	curl -i -X POST -d j_username=temporary -d j_password=temporary -c ./cookies.txt http://localhost:8080/spri-sec-rest-api/j_spring_security_check

	curl -i -H "Content-Type:application/json" -X GET -b ./cookies.txt http://localhost:8080/spri-sec-rest-api/api/customer

	curl -i -H "Content-Type:application/json" -X GET http://localhost:8080/spri-sec-rest-api/api/customer
