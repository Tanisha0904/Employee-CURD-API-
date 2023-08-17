
# Employee_CURD_API
Building REST services with Spring

To launch the application, either right-click the public static void main in PayRollApplication and select Run

$ ./mvnw clean spring-boot:run
or
$ mvn clean spring-boot:run


$ curl -v localhost:8080/employees


POST:
curl -v -X POST localhost:8080/employees -H "Content-Type: application/json" -d "{\"name\": \"Samwise Gamgee\", \"role\": \"gardener\"}"

PUT:
curl -v -X PUT localhost:8080/employees/3 -H "Content-Type: application/json" -d "{\"name\": \"Samwise Gamgee\", \"role\": \"ring bearer\"}"

DELETE:
$ curl -X DELETE localhost:8080/employees/3

