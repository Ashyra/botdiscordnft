## Run with Docker
Edit .env file (Keep database default values if you want to use an embedded database for test purpose)

```sh
docker-compose up
```

## Run with Maven
Edit src/main/application.properties then
```sh
mvn spring-boot:run
```

## Test
```sh
mvn test
```

## Build
```sh
mvn clean install
```