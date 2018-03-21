# Maven Java Basic Archetype

Basic Maven Archetype to create a Java project with well-known test libraries.

More information and detailed instructions: [https://thepracticaldeveloper.com/archetypes](https://thepracticaldeveloper.com/archetypes/)

## Options

You can create a basic Maven Java project using Java 8 or 9, this property can be set when generating the project. 

To use this Archetype directly from Maven Repository, you just need to run:

`mvn archetype:generate -DgroupId=[your-project-groupId] -DartifactId=[your-project-name] -DarchetypeGroupId=com.thepracticaldeveloper -DarchetypeArtifactId=archetype-java-basic-tpd -DarchetypeVersion=1.0.0`

## Included libraries

This archetype includes the libraries:

* JUnit 4
* Mockito
* AssertJ

## Manifest file

The archetype also includes a manifest file so you can run your jar file as a java executable. 
