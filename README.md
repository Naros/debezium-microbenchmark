[![License](http://img.shields.io/:license-apache%202.0-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.debezium/debezium-microbenchmark/badge.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22io.debezium%22)
[![Build Status](https://github.com/debezium/debezium-microbenchmark/workflows/Maven%20CI/badge.svg?branch=master)](https://github.com/debezium/debezium-microbenchmark/actions)
[![User chat](https://img.shields.io/badge/chat-users-brightgreen.svg)](https://gitter.im/debezium/user)
[![Developer chat](https://img.shields.io/badge/chat-devs-brightgreen.svg)](https://gitter.im/debezium/dev)
[![Google Group](https://img.shields.io/:mailing%20list-debezium-brightgreen.svg)](https://groups.google.com/forum/#!forum/debezium)
[![Stack Overflow](http://img.shields.io/:stack%20overflow-debezium-brightgreen.svg)](http://stackoverflow.com/questions/tagged/debezium)

Copyright Debezium Authors.
Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

# Debezium Microbenchmark

Debezium is an open source project that provides a low latency data streaming platform for change data capture (CDC).

This repository contains several JMH benchmarks for portions of Debezium and its connectors.

## Building The Benchmark

Please see the [README.md](https://github.com/debezium/debezium#building-debezium) in the main repository for general instructions on building Debezium from source (prerequisites, usage of Docker etc).

## Running the benchmarks

This project will build a composite jar called `debezium-microbenchmark.jar` that contains all the necessary components to perform the JMH tests.
To run the benchmarks, simply open a terminal window and navigate to the project's root directory and run:

```
java -jar target/debezium-microbenchmark.jar
```

