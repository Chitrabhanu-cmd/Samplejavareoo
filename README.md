# Samplejavareoo

A minimal Java 17 "Hello, world!" project built with Maven.

## Run

```sh
mvn test
mvn package
java -cp target/classes com.example.App
```

The project uses JUnit Jupiter for tests. Run `mvn test` to download dependencies
and execute the sample test.

## Run with Docker

```sh
docker build -t samplejavareoo .
docker run --rm samplejavareoo
```
