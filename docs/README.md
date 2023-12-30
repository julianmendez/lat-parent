# [LAT parent](https://julianmendez.github.io/lat-parent/)
*LAT parent project*

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.txt)
[![Maven Central](https://img.shields.io/maven-central/v/de.tu-dresden.inf.lat/lat-parent.svg?label=Maven%20Central)](https://search.maven.org/artifact/de.tu-dresden.inf.lat/lat-parent)
[![build](https://github.com/julianmendez/lat-parent/workflows/Java%20CI/badge.svg)](https://github.com/julianmendez/lat-parent/actions)

The POM file of this project is used as parent of other project parent POM files.


## Download

* [The Central Repository](https://repo1.maven.org/maven2/de/tu-dresden/inf/lat/lat-parent/)
* as parent

```xml
<parent>
  <groupId>de.tu-dresden.inf.lat</groupId>
  <artifactId>lat-parent</artifactId>
  <version>0.1.7</version>
  <relativePath></relativePath>
</parent>
```


## Source code

To clone the project:

```
$ git clone https://github.com/julianmendez/lat-parent.git
```

The bundles uploaded to [Sonatype](https://oss.sonatype.org/) are created with:

```
$ mvn clean install -DperformRelease=true
```

and then:

```
$ cd target
$ jar -cf bundle.jar lat-parent-*
```

The version number is updated with:

```
$ mvn versions:set -DnewVersion=NEW_VERSION
```

where *NEW_VERSION* is the new version.


## Author

[Julian Alfredo Mendez](https://julianmendez.github.io)


## License

This software is distributed under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).


## Contact

In case you need more information, please contact [julianmendez](https://github.com/julianmendez).


