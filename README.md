Nashorn [![Build Status](https://travis-ci.org/exstar/nashorn.svg?branch=master)](https://travis-ci.org/exstar/nashorn)
=======

This repository is a fork of Oracles Nashorn engine (specifies EcmaScript 5.1 / comes with Java 8 / JDK8, accessible via JSR223). Unlike the original engine, this version is able to run on Java 7 / JDK7. The original backport is done by <a href="https://bitbucket.org/ramonza/nashorn-backport">Ramonza</a>. It is released under the GPLv2.

=======

### Building
#### Prerequires
 * Java SDK 7 (JDK7)
 * Git

#### Cloning
First, clone the repository to you machine. To do that, setup Git, and run the following in your terminal:

    $ git clone https://github.com/exstar/nashorn.git
    $ cd nashorn

#### Compiling
Next, build the project using the Gradle wrapper:

On *nix:

    $ sh gradlew

On Windows:

    ../nashorn>gradlew.bat

Alternative (MinGW/Cygwin for Windows):

    $ bash gradlew
