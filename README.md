# rlabs-flyway-spring-boot

##### Version 0.0.1

Flyway with Spring Boot Application 2.0.<br>
This is an example how to work with database migrations with [Flyway](https://flywaydb.org/) and [Spring Boot](https://projects.spring.io/spring-boot/).<br>

It's based on PostgreSQL database-server, then you should check if the server is up and running.<br>
By the way, the Flyway doesn't create the database, its need to be created outside, as well as setting the username and password for the owner of the data resource. In the future, you can easily switch this example to make use of another database by setting up the correct JDBC driver and Connection URL.<br>

## Execution 

For execute, simple follow the statement:<br>

$ mvn clean compile flyway:migrate<br>
$ mvn clean compile flyway:info
<br><br>
More details can be found on [Flyway Documentation](https://flywaydb.org/documentation/).<br>
Spring Boot Flyway database migrations on startup details can be found on [here](https://docs.spring.io/spring-boot/docs/current/reference/html/howto-database-initialization.html#howto-execute-flyway-database-migrations-on-startup).<br>

## Requirements

- Java 1.8 or later.
- PostgreSQL Server 9.x or later.
- Maven 3.x or later.

## License

This project is developed for education and PoC goals.

Copyright 2017 © ResearchLabs under [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0)

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## About the author

[Ryan Padilha](http://ryanpadilha.com.br) is a JavaEE expert, SOA specialist and techinal writter.<br>
Experience of 12+ years in solution design and development software.<br>
Working nowadays on Software Architecture, Cloud Computing and Micro Services.
