# Protobuf Samples #

>
> This repository is an integral part of the "High performance web services with Swift and Protocol Buffers" article available on [Codete Blog](https://codete.com/blog/).
>

This repository contains code samples used in the "High performance web services with Swift and Protocol Buffers" article. The server application was written in [Swift](https://swift.org/) and uses [Kitura](http://www.kitura.io/) as a web framework and [Swift Protobuf](https://github.com/apple/swift-protobuf) for serialization.

## Repository structure ##

* `protobuf-server` - the server application written in Swift and Kitura
* `protobuf-client` - the iOS client application written in Swift
* `protobuf-gatling` - load tests in Gatling

## Protobuf Sample Server ##

It is a sample Kitura application serving enpoints that can work with JSON or Protobuf depending on the `Accept` header.

### Requirements ###

* Swift 3.1
* Swift Package Manager
* macOS or Linux (Ubuntu) OS
* Ruby (for generating data assets only)

More information about the server application in the [README file](protobuf-server/README.md).

## Protobuf Sample iOS Application ##

It is a sample iOS application that gets data from the server in JSON or Protobuf format.

### Requirements ###

* Sample Protobuf Server running
* Xcode 8.3
* Swift 3.1
* Cocoapods 1.2.0

More information about the client application in the [README file](protobuf-client/README.md).

## Protobuf Sample Gatling Load Tests ##

These are sample load tests for the sample server. It is generated by Gatling Recorder and can be run via sbt.

### Requirements ###

* sbt
* Scala
* Protobuf Sample Server running

More information about the load tests in the [README file](protobuf-gatling/README.md).

## License ##

The source code is licensed under the MIT Licence. More information in the LICENSE file.