#car-reg-spring-security-jpa-mysql

#WebMvcController.java
#=====================
Sets up how each of the java endpoints is mapped to a front-end view (html page) 

#WebSecurityConfig.java
#======================
extends on WebSecurityConfigurerAdapter
inserts in memory the user details user:"user" and password:"password"

everyone has view permissions on "/" and the "home.html" page, eg localhost http://localhost:8080
if an attempt is made to view any other page the login page is called "/login"
 
