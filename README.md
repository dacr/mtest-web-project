# mtest-dep

small fake java dependency to be built with maven.

```
mvn test
mvn package
mvn install
```


this fake web application has been generated using this maven archetype :
```bash
mvn archetype:generate \
     -DgroupId=mtestwebproject \
     -DartifactId=mtest-web-project \
     -DarchetypeArtifactId=maven-archetype-webapp \
     -DinteractiveMode=false
```

With a small Addition to allow execution from maven, with the integration of jetty

```
mvn test
mvn package
mvn jetty:run
```

