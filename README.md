# JHTTP                  


JHTTP is a simple HTTP server written in the Java 8.

## Requirements

* Java 8 SDK
* Maven
* things n' stuff

## Building

    mvn clean package
 
It creates a self-contained, executable JAR in the `target` directory.

## Usage

    usage: java -jar jhttp*.jar [-h] [-p <PORT>] [-r <DIR>] [-t <THREADS_NO>]
    Starts a simple HTTP server
    -h,--help                   display help
    -p,--port <PORT>            port to listen (default: 8888)
    -r,--root <DIR>             server root directory (default: '.')
    -t,--threads <THREADS_NO>   thread pool size (default: 10)
    
### Demo
* [Change background color](src/main/java/io/harness/jhttp/processor/DirectoryListing.java)
* [Update a test](src/test/java/io/harness/jhttp/server/HeaderListTest.java)
* [Update README](README.md) Test3   

# delete this
