# Spring Boot LDAP Demo
    This project is aimed at demonstrating LDAP security in spring boot application.
    It works with embedded Java-based LDAP server.
    App will load the LDAP server with a data file that contains a set of users.

### Document Reference
    Please erefer the below link for the spring boot documentation.

[Spring Boot LDAP Documentation](https://spring.io/guides/gs/authenticating-ldap/)

### Pre-Requisites
    Please refer the respective LDAP provider documentation to get client id and secret id.

### Build and Run
    mvn clean install
    mvvn spring-boot:run

### Test
    We can test by opening the url http://localhost:8080/ in browser
