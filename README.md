# sample-sb-1-5-with-spock-testing

Calculates a tip over REST, tested with Spock.

## Stack

- Spring Boot 1.5.22.RELEASE
- Java 8
- Gradle 3.5.1
- Spock 1.0-groovy-2.4

## Build

```
./gradlew build
```

## Run

```
./gradlew bootRun
```

```
curl 'localhost:8080/tip?bill=20.00&percent=15'
```
