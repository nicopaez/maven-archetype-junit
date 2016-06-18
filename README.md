# Maven archetype for class library projects

This archetype creates a simple maven project with the following dependencies:

* JUnit 4.11
* Mockito 1.9.5
* Cobertura 2.0.3

The projects created with this archetype with include a sample class with its corresponder JUnit test.

To install this archetype:

````
mvn install

mvn archetype:update-local-catalog
````

Once installed, you can use it with the following command:


````
mvn archetype:generate \
-DarchetypeGroupId=com.nicopaez.tutorials \
-DarchetypeArtifactId=junit-quickstart \
-DarchetypeVersion=1.0.0
````


For feedback or support you can contact nicopaez_at_computer.org


