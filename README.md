# Recruitment App Service

The service has eight APIs divided into two base handlers "/candidate" and "/user" for creating application, updating application status, creating offer, viewing offers, viewing applications, etc.

* Base URL = http://localhost:8080/recruitmentapp
* Error Codes :
		200 : Success
		201 : Created resource
		400 : Bad request
		500 : Server error

* There are eight APIs, base urls and methods are mentioned below :
1. URL : "/candidate/create-application", Method: POST
2. URL : "/candidate/application-status/{id}", Method: GET
3. URL : "/user/create-offer", Method: POST
4. URL : "/user/view-offer/{id}", Method: GET
5. URL : "/user/view--all-offers", Method: GET
6. URL : "/user/view-application", Method: GET
7. URL : "/user/view-all-applications", Method: GET
8. URL : "/user/update-status", Method: POST

* Database configurations :

spring.datasource.url = "jdbc url"
spring.datasource.username="username"
spring.datasource.password="password"

spring.jpa.show-sql = true
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL5Dialect

