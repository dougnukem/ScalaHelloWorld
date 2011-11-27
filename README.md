# Scala Hello World Test

This is a basic example project to learn how to setup a Scala project that uses 
Ant and Ivy to build from the command-line and can integrate into the Eclipse IDE,
using the Scala IDE plugin.

Before starting eclipse you should build using Ant so that the relevant scala libraries are available.

    ant build

This will download the Scala compiler and library to the lib/ folder in the project which is referenced in the
Eclipse projects .classpath .

In Eclipse you should be able to "Import Existing Projects" and point it to this project directory.

## Dependencies
 * [Apache Ant](http://ant.apache.org/)
 * [Scala IDE](http://www.scala-ide.org/)
 * [IvyDE](http://ant.apache.org/ivy/ivyde/)
