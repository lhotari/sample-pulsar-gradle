# Sample Gradle build for Pulsar experiments

### Starting/Stopping Pulsar

Starts Pulsar in docker
```bash
./gradlew pulsarStart
```

You can view Pulsar container logs with this command
```bash
docker logs -f pulsar-test
```

Stopping and removing Pulsar container
```bash
./gradlew pulsarStop
```

### Running the application

```bash
./gradlew run
```

### Packaging in single jar

```bash
./gradlew shadowJar
```
result is build/libs/sample-pulsar-gradle-all.jar
