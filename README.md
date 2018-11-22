# spring-boot-consume-rest-endpoint

If you do not have lombok installed in your IDE, it might show warnings.

Ideally keep the [application.properties](application.properties) file as : 

spring.jpa.database-platform=org.hibernate.dialect.MySQL5Dialect
spring.jpa.hibernate.ddl-auto=create-drop
spring.datasource.url=jdbc:mysql://localhost:3306/spring
spring.datasource.username=${DB_USER}
spring.datasource.password=${DB_PASSWD}
