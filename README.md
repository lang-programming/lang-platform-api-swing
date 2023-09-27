# lang-platform-api-swing
LangPlatformAPI implentation of at.jddev0.lang:lang-interpreter for the Java Swing GUI library

## Use as dependency

**Maven**
```xml
<dependency>
    <groupId>at.jddev0.lang</groupId>
    <artifactId>lang-platform-api-swing</artifactId>
    <version>1.0.0-beta-03</version>
</dependency>
```
**Gradle**
```groovy
implementation 'at.jddev0.lang:lang-platform-api-swing:1.0.0-beta-03'
```

## Build from Source

- Execute the following command
```bash
./gradlew publishToMavenLocal
```
- `mavenLocal()` must be in the `repositories` section of the `build.gradle` file of the project you'd like to use the locally compiled version.