# Cinema App
This is a web application called "Cinema App" that allows users to register in the system and have their own personal cart where they can add tickets for movie screenings, choose cinema halls, search for specific movie screenings by date and movie, and more. It enables users to authenticate themselves with a login and password after registration. Each user also has a role (USER/ADMIN).

The admin has additional privileges while using this web application. 😎

This application operates using the Spring Framework, Hibernate ORM Framework, Apache Tomcat, and MySQL database.

## Getting Started

To run the application, the following prerequisites are needed:

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- Apache Tomcat 9.0.50
- MySQL 8 or later
- Maven

### Installation

1. Clone the repository using the command `git clone https://github.com/Iskamele/cinema-app`

2. Open the project in your preferred IDE and build the project

3. Configure `src/main/resources/db.properties` file

#### For local start:

1. run tomcat.

2. to log in to cinema-app: [here](http://localhost:8080/login)

3. to log in with ADMIN role use admin@i.ua : admin123

4. to log in with USER role use user@i.ua :user123

5. to log out: [here](http://localhost:8080/logout)

#### For remote start:

1. Build the project using Maven:
```
mvn clean package
```

2. Deploy the WAR file to your local Tomcat server.

3. Start the Tomcat server and go to [http://hostname:port/cinema-app](http://localhost:8080/cinema-app) in your web browser

### Hey Hey Hey Hey Hey Hey Hey 🤓

To create, delete or get entities use [postman](https://www.postman.com/) or other service with POST/DELETE/GET requests and right end-points

## Features

- Add, delete, and view cinema halls, movies, movie sessions, orders, and users.
- Basic authentication and session management.
- BCryptPasswordEncoder
- Connection pooling and error handling.
- Custom exception handling.

## Technologies

The project uses the following technologies:

- Java 17
- MySQL
- Hibernate ORM Framework
- Spring Framework
- Spring MVC/Security
- REST
- Apache Tomcat
- Maven
- Jackson
- JSON

## Contributing <a name="contributing"></a>

Contributions to the project are welcome. You can fork the repository, make changes, and submit a pull request.

## License <a name="license"></a>

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Iskamele/cinema-app/blob/main/LICENSE) file for details.
