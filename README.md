# simple demo app for quarkus 2.16.6.Final


## quick start

Following the quarkus [getting started guide](https://quarkus.io/guides/getting-started).

Tested on : 
* Apache Maven 3.8.7
* Amazon Corretto JDK 11.0.18


**1 - Project creation : **

```
mvn io.quarkus.platform:quarkus-maven-plugin:2.16.6.Final:create \
    -DprojectGroupId=org.fugerit.java \
    -DprojectArtifactId=quarkus-2.16.6.Final \
    -Dextensions='resteasy-reactive'
```

**2 - Quarkus run :**

```
mvn quarkus:dev
```

**3 - Test :**

You can reach for the test page on [http://localhost:8080/hello](http://localhost:8080/hello)


