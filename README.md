Gradle Publish to Local Maven Demo
===================================

How to publish current project to local maven repository `~/.m2`

```
./gradlew install
```

You will find the generated files under `~/.m2/repository/demos/gradle-publish-to-local-maven-demo/0.1.0`.

Keys
----

- `apply plugin: 'maven'`
- `group = "demos"`
- `version = "0.1.0"`
