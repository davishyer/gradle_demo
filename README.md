# Gradle Demo

Tutorial to help understand the basics of Gradle. Compile, pack, and execute
a simple program using Gradle as the buildscript.

## Part 1 - Basics

Generates a jar file that can be executed. The expected output is an array
of each string provided. Configures the `sourceSets` and `jar` tasks provided
by the java plugin.

## Part 2 - Dependencies

Supports the StringUtils library now being used in the program. Defines where
the dependecy can be found, and which version to use. Unpacks the dependency
to be available to the jar.

## Part 3 - Tasks

Creates three custom tasks.
1. hello - simply print messages. Used to demonstrate the phases of a task.
1. runJar - executes the jar file. Used to demonstrate task dependencies.
1. run - executes the compiled classes. Used as an alternative to the above.

## Resources

This tutorial was *heavily* based on another tutorial that can be found
[here](https://www.youtube.com/watch?v=vxKN2VSqTMg). I highly suggest
watching the three part series.

The original intent of this project was in conjuction with a presentation
that can be found [here](https://docs.google.com/presentation/d/1hxUG2EiC8enXFLfQijd-619j59F5Fd5245gB4wzbpkQ/edit?usp=sharing).