# exo-sonar-rules

## Description
This project is an example for custom Java rules for SonarQube.  
It checks that the CSRF protection is activated for WebUI listeners associated to PROCESS phase.  

## Packaging
```maven
mvn clean package
```
This will generate a jar file in the target folder.

## Usage
Just copy the jar file in the /extensions/plugin folder of your SonarQube installation.  
Note: this example works with SonarQube 5.0.1 with Sonar Java Plugin 3.2 installed.  
