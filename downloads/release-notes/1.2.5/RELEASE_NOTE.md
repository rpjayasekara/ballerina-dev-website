---
layout: release-note
title: Release note
---
# Overview of jBallerina 1.2.5
The jBallerina 1.2.5 patch release improves upon the 1.2.4 release by introducing the features listed below and addressing a couple of [bugs](https://github.com/ballerina-platform/ballerina-lang/issues?q=is%3Aissue+label%3AType%2FBug+milestone%3A%22Ballerina+1.2.5%22+is%3Aclosed+) and [improvements](https://github.com/ballerina-platform/ballerina-lang/issues?q=is%3Aissue+milestone%3A%22Ballerina+1.2.5%22+is%3Aclosed+label%3AType%2FImprovement+).

You can use the update tool to update to jBallerina 1.2.5 as follows.

**For existing users:**
If you are already using jBallerina version 1.2.0, or above, you can directly update your distribution to jBallerina 1.2.5 by executing the following command:

> $ ballerina dist update

However, if you are using

- jBallerina 1.2.0 but switched to a previous version, run `$ ballerina dist pull jballerina-1.2.5` to update.
- a jBallerina version below 1.1.0, install via the [installers](https://ballerina.io/downloads/)

**For new users:**
If you have not installed jBallerina, then download the [installers](https://ballerina.io/downloads/) to install.

## Language
## Standard Library
- The capability to validate the JWT signature with JWKs is extended now. With that, the JWT signature can be validated either from the TrustStore configuration or JWKs configuration.
- Undeprecate the `ballerinax/java.jdbc` module and continue to support it in 1.2.x releases.

## Deployment
- Azure Functions support
- Prometheus support for kubernetes annotations

