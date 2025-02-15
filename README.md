# Kotlin Language Server with Bazel support


This a fork of the [Kotlin Language Server](https://github.com/fwcd/kotlin-language-server) with some preliminary Bazel support in Visual Studio Code. This is still a work in progress.

NOTE: This rips out Gradle/Maven support that exists in the upstream fork to support Bazel.

![Icon](Icon128.png)

Currently only [VSCode](https://github.com/srmocher/vscode-bazel-kotlin) is supported.

## Features
- Autocompletion
- Goto with source jar support
- Tracking and providing information about Kotest test suites and test cases.

This implementation aims to provide high performance by only indexing a small subset of source files tracked by Bazel and compute source code metadata during a build.

## Authors
* [srmocher](https://github.com/srmocher)

All credit to the original authors of [Kotlin Language Server](https://github.com/fwcd/kotlin-language-server) for the original implementation.
