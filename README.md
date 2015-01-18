# ant-build-example
Ant build example

ant run
Buildfile: /Users/home/Documents/projects/ant-build-example/AntExample/build.xml

clean:
   [delete] Deleting directory /Users/home/Documents/projects/ant-build-example/AntExample/bin

compile:
    [mkdir] Created dir: /Users/home/Documents/projects/ant-build-example/AntExample/bin/classes
    [javac] /Users/home/Documents/projects/ant-build-example/AntExample/build.xml:9: warning: 'includeantruntime' was not set, defaulting to build.sysclasspath=last; set to false for repeatable builds
    [javac] Compiling 1 source file to /Users/home/Documents/projects/ant-build-example/AntExample/bin/classes

jar:
    [mkdir] Created dir: /Users/home/Documents/projects/ant-build-example/AntExample/bin/jar
      [jar] Building jar: /Users/home/Documents/projects/ant-build-example/AntExample/bin/jar/HelloWorld.jar

run:
     [java] Hello World !!

BUILD SUCCESSFUL
Total time: 0 seconds

