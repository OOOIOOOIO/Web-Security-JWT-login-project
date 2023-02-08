# Web-Security-JWT-login-project
Login with HTTP Only Cookie &amp; Spring Security &amp; Spring boot by Web Style.

## Project Spec
- java : 11
- Spring Boot : 2.7.6
- Graddle : 7.5.1
- jwt : 0.11.2
- h2 : 2.1.214
- mysql : 8.0.3

<br>

## Domain
- ### User
   - userId / Long 
   - username / String
   - email / String
   - password / String
   - roles / Set<Role>

- ### Role
   - roleId / Long
   - name / Erole
  
- ### RefreshToken
   - refreshId / Long
   - user / User
   - token / String
   - expiryDate / Instant
  
- ### ERole(enum)
   - ROLE_USER
   - ROLE_MODERATOR
   - ROLE_ADMIN


<br>
<hr>
<br>

[1]https://www.bezkoder.com/spring-boot-security-login-jwt/

[2]https://www.bezkoder.com/spring-security-refresh-token/

[시큐리티 버전]https://www.bezkoder.com/websecurityconfigureradapter-deprecated-spring-boot/
