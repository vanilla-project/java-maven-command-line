# Vanilla Java Maven Command Line Project

This repository shows a basic setup for a command line application in Java build with Maven.


## Getting Started

Java 1.8 and Maven are expected to be installed on our system.


### Installing

After cloning this repository, change into the newly created directory and run

```
mvn package
```

This will install all dependencies needed for the project as well as compile all source files into a JAR file.


## Running the Tests

All tests can be run by executing

```
mvn test
```

`mvn` will automatically find all tests inside the `src/test` directory and run them.


## Built With

- [Java](https://www.java.com)
- [Maven](https://maven.apache.org)
- [JUnit](http://junit.org)


## License

This project is licensed under the MIT License - see the [license.md](license.md) file for details.
