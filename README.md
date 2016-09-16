SwiftUtils
==========

Utility Library in Swift (3.0+).

By Thanh Ba Nguyen (btnguyen2k (at) gmail.com).

Project home:
[https://github.com/btnguyen2k/swiftutils](https://github.com/btnguyen2k/swiftutils)


## License ##

See LICENSE.txt for details. Copyright (c) 2016 Thanh Ba Nguyen.

Third party libraries are distributed under their own license(s).


## Release Notes ##

Latest release version: `1.1.1`. See [RELEASE-NOTES.md](RELEASE-NOTES.md) for details.

Notes: Swift 3+ is required!


DateTimeUtils
-------------

Date & time utility class. See [README-DateTimeUtils.md](README-DateTimeUtils.md).


SnowflakeIdGenerator
--------------------

Swift implementation of Twitter's Snowflake algorithm. See [README-SnowflakeIdGenerator.md](README-SnowflakeIdGenerator.md).


SyncUtils
---------

* Synchronizes a code block: *

```swift
let result = synchronizd(lockObj) {
//     .... code here ....
}
```
