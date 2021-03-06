canadensys-core
===============

Collection of utility functions used by Canadensys projects.

Code Status
-----------
[![Build Status](https://travis-ci.org/Canadensys/canadensys-core.png)](https://travis-ci.org/Canadensys/canadensys-core)

Features
--------
* Zip an entire folder (and its contents)
* UTF-8 and in-memory ResourceBundle
* Generic number parser : T parseNumber(String value, Class<T> targetClass)
* Roman numerals support
* Enum for continents, provinces/states of Canada, US, Belgium and Colombia

Usage
-----
Maven
```
<dependency>
	<groupId>net.canadensys</groupId>
	<artifactId>canadensys-core</artifactId>
	<version>1.8</version>
</dependency>
```

Dependencies
------------
* [Apache Commons Lang 3.2.1](http://commons.apache.org/lang/)
* [Apache Commons Compress 1.4.1](http://commons.apache.org/compress/)
* [Apache Commons IO 2.4](http://commons.apache.org/io/)
* [Apache Maven 3](http://maven.apache.org/)

How to Contribute
-----------------
See this [page](https://github.com/Canadensys/canadensys-core/wiki/How-to-contribute) for all the information.

Build
-----
```
mvn package
```

Tests
-----
Unit tests
```
mvn test
```

Contributors
-----------
* Thoralf Gutierrez - Roman Numerals converter
