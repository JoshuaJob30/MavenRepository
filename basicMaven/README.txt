1.) To create Maven project:
mvn archetype:generate -DgroupId=com.wipro.topgear -DartifactId=basicMaven -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

Created basicMaven project

To build the project:
mvn clean install

2.) To run Main class
mvn exec:java  -Dexec.mainClass=com.wipro.topgear.App

3.) To run Test class
mvn -e -Dtest=com.wipro.topgear.TestApp#testApp -DfailIfNoTests=false test
