# JMH Demo

## Initial project
```bash
$ mvn archetype:generate
          -DinteractiveMode=false
          -DarchetypeGroupId=org.openjdk.jmh
          -DarchetypeArtifactId=jmh-java-benchmark-archetype
          -DgroupId=your.group.id
          -DartifactId=your-artifact-id
          -Dversion=1.0
```
## Build project
```bash
mvn clean install
```

## Run JMH project
```bash
java -jar target/benchmarks.jar
```
