# Jenclight

Light-weight Jenkins client for Java, based on Jenkins REST API

-----

After googling for a few days I found it hard to get a jenkins rest api client for java without a dozen of dependencies, the offical client com.offbytwo.jenkins caused me lots of classpath conflicts with aws sdk, kafka java sdk etc. To fix these classpath conflicts, Instead of rewriting another aws sdk or kafka sdk which to me is too much to complete, jenkins seems to be the easy answer. After just 1 day coding, I managed to create this light weight jenkins rest api client ---jenclight. Currently it supports: 

* basic http authentication with account username, password/api-token
* build job with or without parameters
* customizable jenkins log handler
* customizable jenkins job progress handler
* job timeout config

## Quick Start

the [Demo](https://github.com/logicigam/jenclight/blob/master/src/test/java/org/k1/jenclight/Demo.java) class in the source code provides most of the common use cases of how-to


