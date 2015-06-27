ProtoParser
===========

Java parser for `.proto` schema declarations.

`ProtoParser` will parse a standalone `File` or schema data directly and return an object
representation as a `ProtoFile` instance.


Download
--------

Download [the latest .jar][dl] or depend via Maven:
```xml
<dependency>
  <groupId>com.squareup</groupId>
  <artifactId>protoparser</artifactId>
  <version>4.0.2</version>
</dependency>
```
or via Gradle:
```groovy
compile 'com.squareup:protoparser:4.0.2'
```

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snap].



License
-------

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



 [dl]: https://search.maven.org/remote_content?g=com.squareup&a=protoparser&v=LATEST
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/
