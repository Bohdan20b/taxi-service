# 🚕 Taxi-service 
### 📗 ***Project description***
```
Taxi service is a web-application that supports authentication, registration and CRUD operations.
```
Non-authorized users are able to:
* login to the service with existing credentials
* register a new account

List of options available for logged users:
* Display all drivers
* Display all cars
* Display all driver's cars
* Display all manufacturers
* CRUD for driver
* CRUD for car
* CRUD for manufacturer
* Add driver to car

### 💾 ***Project's structure***

Based on 3-layer architecture:
* Presentation layer - controllers.
* Application layer - services.
* Data access layer - DAO.

User can always log out using ***logout*** button in header of each page.

### 🔨 ***Project launch:***

1. Clone this project to your IDE as Maven project. *Hint: If you use IntelliJ IDEA, use only Ultimate version*
2. Open pom.xml and reload all maven projects.
3. Set a new configuration, use Tomcat Local Server and select war-exploded artifact to deploy. Application content parameter should be like this "/".
4. Initialize DB. Using provided SQL script in init.db create a DB in MySQLWorkbench.
5. In order to create connection between project and DB, set your credentials in ConnectionUtil class.

```
    private static final String URL = "YOUR_DATABASE_URL";
    private static final String USERNAME = "YOUR_USERNAME";
    private static final String PASSWORD = "YOUR_PASSWORD";
```
6. Build project.

### 🧰 Application technologies:
* **[JDK 11 or higher](https://www.oracle.com/cis/java/technologies/javase/jdk11-archive-downloads.html)**
* **[Apache Maven](https://maven.apache.org/download.cgi)**
* **[Apache Tomcat (required: 9.0.50)](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)**
* **[MySQL](https://dev.mysql.com/downloads/workbench/)**
* **[Java Servlet API » 4.0.1](https://mvnrepository.com/artifact/javax.servlet/javax.servlet-api/4.0.1)**
* **[JSTL JavaServer Pages Standard Tag Library](https://mvnrepository.com/artifact/jstl/jstl/1.2)**
