Ballerina FTP Library
=====================

  [![Build](https://github.com/ballerina-platform/module-ballerina-ftp/workflows/Build%20master%20branch/badge.svg)](https://github.com/ballerina-platform/module-ballerina-ftp/actions?query=workflow%3ABuild)
  [![Daily build](https://github.com/ballerina-platform/module-ballerina-ftp/workflows/Daily%20build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-ftp/actions?query=workflow%3A%22Daily+build%22)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-ftp.svg)](https://github.com/ballerina-platform/module-ballerina-ftp/commits/master)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The ftp library is one of the standard library modules of the<a target="_blank" href="https://ballerina.io/"> Ballerina</a> language.

It provides implementation for file manipulation related operations over network using FTP protocol.

For more information go to [The FTP Module](https://ballerina.io/swan-lake/learn/api-docs/ballerina/ftp/index.html).

For example demonstrations of the usage, go to [Ballerina By Examples](https://ballerina.io/swan-lake/learn/by-example/).

## Building from the Source

### Setting Up the Prerequisites

1. Download and install Java SE Development Kit (JDK) version 11 (from one of the following locations).

   * [Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

   * [OpenJDK](https://adoptopenjdk.net/)

        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.
     
### Building the Source

Execute the commands below to build from source.

1. To build the library:

    ```shell script
        ./gradlew clean build
    ```

2. To run the unit tests:

    ```shell script
        ./gradlew clean test
    ```

3. To build the module without the tests:

    ```shell script
        ./gradlew clean build -x test
    ```

4. To debug the tests:

    ```shell script
        ./gradlew clean test -Pdebug=<port>
    ```

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

You can also check for [open issues](https://github.com/ballerina-platform/module-ballerina-ftp/issues) that interest you. We look forward to receiving your contributions.

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss about code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
