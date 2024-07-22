# Maven-from-Base
This repository serves as a hands-on learning environment of the foundational concepts of Maven 

What is the process of building a Java file?

1) writing the source code : The process starts with writing the java source code in .java
2) compilation : the source code is compiled into bytecide using "javac" compiler, producing ".class" files
3) packaging : the compiled classes, along with the other resources like configuration files, are packaged into a JAR(Java Archive) or WAR (Web Archive) file.
4) Testing : Automated tests are run to ensure the code brhaves as expected
5) Deplyment : The packaged application is deployed to a runtime environment.

Why do we use a build tool for a java project ?

Build tools automate the process of buidling and managing projects, providing several benefits.

1) dependency Management : Automatically downloads and includes necessory libraries.
2) Consistent Builds : Ensures the same build process and includes necessory libraries.
3) Automation: Automates repitive tasks like compilations, Packaging, and testing.
4) Project Configuration : Standardizes project structrure and Configurations.

Maven Build Life cycle 

When we build a maven project, it executes a set of clearly defined tasks based on the project pom.xml configuration and the commadn-line options. This standard set of tasks creates the maven build lifecycle. The benefit of a clearly defined life cycle is that we have to remember only a few sets of commands to compile, build, install, and deploy our projects.

Build-in Build lifecycles

There are three built-in-build lifecycles.

1) Default : handles project build and deployment
2) clean : Handles project cleaning
3) site: handles the creation of project site documentation.

Maven Build Phases 

Maven build lifecycle goes through a set of stages, they are called build phases. For example, the default lifecycle is made up of the following phases 
Validate - Checks if the project is correct and all necessory infromation is available  
         - Ensures the project directory structure and required files are in place.

Compile - Compiles the source code of the project , convert the java files to bytecode (.class) files 
Test - Runs the unit tests using necessory test frameworks 
Package - packages the compiled code to a distributable format, like a JAR or WAR file.
Verify - Runs any checks to verify the packae is valid and meets quality criteria 
Install - install the package into the local maven repository 
Deploy - copies the final package into the remote repository 




