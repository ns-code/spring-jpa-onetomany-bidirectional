# spring-jpa-onetomany-bidirectional
This project is a Spring Data JPA OneToMany bi-directional relationship example. The OneToMany relationship between Customer and Contact entities is implemented using @ManyToOne in the child Contact and @OneToMany in the parent Customer. Uses an embedded H2 database.

## Build and Test
```
.\gradlew clean build

.\gradlew test
```

## Build and Run Swagger UI
All CRUD APIs for the two entities can be tested using the Swagger UI.
```
.\gradlew bootRun

http://localhost:8080/swagger-ui/index.html
```

## Browse DB Tables
```
.\gradlew bootRun

http://localhost:8080/h2-console
```

## Related Projects
OneToMany uni-directional relationship example:<br>
https://github.com/ns-code/spring-jpa-onetomany-unidirectional

ManyToMany Bi-Directional relationships example:<br>
https://github.com/ns-code/spring-jpa-courseenrollments

ManyToMany Bi-Directional relationships modeled using composite keys:<br>
https://github.com/ns-code/spring-jpa-courseenrollments-2

