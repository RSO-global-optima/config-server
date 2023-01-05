# Global Optima - Config microservice
### Goals
- Configuration with consul

---

### Requirements
- Java openjdk-19.0.1
- Maven 3.8.6
- Running consul server on localhost  
  `consul agent -dev -ui`


Check the correct versions with `mvn --version`

### How to run
- build the project `mvn clean package`
- run locally `java -jar target/delivery-server-1.0-SNAPSHOT.jar`  
  Service can be accessed via [http://localhost:8080/config](http://localhost:8080/config)

