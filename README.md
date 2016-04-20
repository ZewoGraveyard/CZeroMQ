CZeroMQ
======

[![Swift 3.0](https://img.shields.io/badge/Swift-3.0-orange.svg?style=flat)](https://swift.org)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://swift.org)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](http://slack.zewo.io/badge.svg)](http://slack.zewo.io)

**CZeroMQ** provides ZeroMQ for **Swift 3.0**.

## Installation


```bash
$ sudo apt-get install libzmq3-dev
```

- Add `CZeroMQ` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/CZeroMQ.git", majorVersion: 1)
	]
)

```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](http://slack.zewo.io)

Join us on [Slack](http://slack.zewo.io).

License
-------

**CZeroMQ** is released under the MIT license. See LICENSE for details.
