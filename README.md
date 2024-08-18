Skeleton Stapler Application
============================

This is a minimum 'hello world' Java web application written with Stapler.
If you are creating a new application, you can start with this skeleton:

    $ java -version
    openjdk version "1.8.0_382"
    OpenJDK Runtime Environment Corretto-8.382.05.1 (build 1.8.0_382-b05)
    OpenJDK 64-Bit Server VM Corretto-8.382.05.1 (build 25.382-b05, mixed mode)

    $ git init
    $ git pull https://github.com/stapler/stapler-archetype.git master

Building
--------

Run `mvn package` to build a war, and run `mvn jetty:run` to run this application
in place on localhost:8080.
