## microservice-testing
This Readme file contains RestAssured Framework in BDD Approach.

#### Requirements to run API's on localhost
1. Downloading and installing mongodb Database for using DB and compass for monitoring it (GUI) 1.1) https://www.mongodb.com/try/download/community 1.2) https://www.mongodb.com/try/download/compass
2. Depedency of spring boot webflux.
3. Lombok dependency and integrating Lombok to IDE

#### Test Framework
##### Structure
This project is a standard Gradle Java project with src folders and Gradle.build.
##### Tests
1. src/test/java/ holds test classes using TestNG.
2. src/main/java holds Random generated test data for API's, utilites and configs.
3. Extent Reports will be generated after every test run, to show the passed and failed test scripts.
