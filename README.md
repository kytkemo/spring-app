# spring-app

Maven archetype for a Spring App (Java 7).

## Install

Install to local repository with `mvn clean install`.

## Usage

Create projects from the archetype with the following command:

    mvn archetype:generate -DarchetypeGroupId=com.kytkemo
                           -DarchetypeArtifactId=spring-app
                           -DarchetypeVersion=1.0.7
                           -DarchetypeRepository=local
                           -DgroupId=com.yourcompany
                           -DartifactId=ProjectName
                           -Dpackage=com.yourcompany.projectname

## Developing a project

After creating a project from the archetype you can do the following tasks.

### Run tests

Run tests with `mvn test`.

### Build

Create a package with `mvn package`.
