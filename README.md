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





