<p align="center"><a href="https://maven.apache.org" target="_blank"><img src="https://maven.apache.org/images/apache-maven-project.png" width="400"></a></p>

<p align="center">
[![Reproducible Builds](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/jvm-repo-rebuild/reproducible-central/master/content/org/apache/maven/maven/badge.json)](https://github.com/jvm-repo-rebuild/reproducible-central/blob/master/content/org/apache/maven/maven/README.md)
</p>

## Apache Maven

Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

- [master](https://github.com/apache/maven) = 4.1.x: [![Maven Central](https://img.shields.io/maven-central/v/org.apache.maven/apache-maven.svg?label=Maven%20Central)](https://central.sonatype.com/artifact/org.apache.maven/apache-maven)
[![Jenkins Status](https://img.shields.io/jenkins/s/https/ci-maven.apache.org/job/Maven/job/maven-box/job/maven/job/master.svg?)][build]
[![Jenkins tests](https://img.shields.io/jenkins/t/https/ci-maven.apache.org/job/Maven/job/maven-box/job/maven/job/master.svg?)][test-results]
- [4.0.x](https://github.com/apache/maven/tree/maven-4.0.x): [![Maven Central](https://img.shields.io/maven-central/v/org.apache.maven/apache-maven.svg?label=Maven%20Central&versionPrefix=4.0)](https://central.sonatype.com/artifact/org.apache.maven/apache-maven)
- [3.9.x](https://github.com/apache/maven/tree/maven-3.9.x): [![Maven Central](https://img.shields.io/maven-central/v/org.apache.maven/apache-maven.svg?label=Maven%20Central&versionPrefix=3.)](https://central.sonatype.com/artifact/org.apache.maven/apache-maven)


## Learning Laravel

More information can be found on [Apache Maven Homepage][maven-home]. Questions related to the usage of Maven should be posted on the [Maven User List][users-list].

## Quick Build

If you want to bootstrap Maven, you'll need:
- Java 17+
- Maven 3.6.3 or later
- Run Maven, specifying a location into which the completed Maven distro should be installed:
    ```
    mvn -DdistributionTargetDir="$HOME/app/maven/apache-maven-4.1.x-SNAPSHOT" clean package
    ```


```bash
npm ci
npm run dev


# listening at localhost:3000
```










# java
java LTS


# maven - Official Image
# Safe choices for Java 8 apps:
# - Maven 3.6.3 (most widely used for Java 8)
# - Maven 3.8.6 (still Java 8 compatible, newer)

# - Maven 3.6.3 (do not support Java 11)
# - Maven 3.8.6 (widely used, stable with Java 11)
# - Maven 3.9.9 (recommended if you want up-to-date fixes and compatibility with modern plugins)

# - Maven 3.8.1 (Minimum supported Java 17)
# - Maven 3.8.6 (widely used, stable with Java 17)
# - Maven 3.9.9 (recommended if you want up-to-date fixes and compatibility with modern plugins)

# - Maven 3.9.0 (Minimum supported Java 21)
# - Maven 3.9.6 (widely used, stable with Java 21)
# - Maven 3.9.9 (recommended if you want up-to-date fixes and compatibility with modern plugins)




## eclipse-temurin - Official Image
# maven:3.3-jdk-7
# maven:3.8.6-eclipse-temurin-8
# maven:3.8.6-eclipse-temurin-11
# maven:3.8.6-eclipse-temurin-17
# maven:3.9.6-eclipse-temurin-21-alpine
# eclipse-temurin:8-jre-alpine 
# eclipse-temurin:11-jre-alpine
# eclipse-temurin:17-jre-alpine
# eclipse-temurin:21-jre-alpine


## create project
# mvn archetype:generate -DgroupId=com.example -DartifactId=my-restapi -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

# mvn clean install -DskipTests 
# mvn compile -DskipTests 
# mvn package -DskipTests





