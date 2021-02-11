Ballerina UDP Library
===================

  [![Build](https://github.com/ballerina-platform/module-ballerina-udp/workflows/Build/badge.svg)](https://github.com/ballerina-platform/module-ballerina-udp/actions?query=workflow%3ABuild)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-udp.svg)](https://github.com/ballerina-platform/module-ballerina-udp/commits/master)
  [![Github issues](https://img.shields.io/github/issues/ballerina-platform/ballerina-standard-library/module/udp.svg?label=Open%20Issues)](https://github.com/ballerina-platform/ballerina-standard-library/labels/module%2Fudp)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The UDP package is one of the standard library packages of the<a target="_blank" href="https://ballerina.io/"> Ballerina</a> language.

This package provides an implementation for sending/receiving messages to/from another application process (local or remote) for connectionless protocols. 

For more information on the operations supported go to [The UDP Package](https://ballerina.io/learn/api-docs/ballerina/udp/).

For example demonstrations of the usage, go to [Ballerina By Examples](https://ballerina.io/learn/by-example/udp-listener.html).


## Issues and Projects 

Issues and Projects tabs are disabled for this repository as this is part of the Ballerina Standard Library. To report bugs, request new features, start new discussions, view project boards, etc. please visit Ballerina Standard Library [parent repository](https://github.com/ballerina-platform/ballerina-standard-library). 

This repository only contains the source code for the package.

## Building from the Source

### Setting Up the Prerequisites

1. Download and install Java SE Development Kit (JDK) version 11 (from one of the following locations).

   * [Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
   
   * [OpenJDK](https://adoptopenjdk.net/)
   
        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.
     

### Building the Source

Execute the commands below to build from source.

1. To build the package:
        
        ./gradlew clean build

2. To build the package without the tests:

        ./gradlew clean build -x test

3. To debug package implementation:

        ./gradlew clean build -Pdebug=<port>
        
## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss about code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
