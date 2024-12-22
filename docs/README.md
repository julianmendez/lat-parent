# [LAT parent](https://julianmendez.github.io/lat-parent/)
*LAT parent project*

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)][license]
[![Maven Central](https://img.shields.io/maven-central/v/de.tu-dresden.inf.lat/lat-parent.svg?label=Maven%20Central)][maven-central]
[![build](https://github.com/julianmendez/lat-parent/workflows/Java%20CI/badge.svg)][build-status]

The POM file of this project is used as parent of other project parent POM files.


## Download

* [The Central Repository][central-repository]
* as parent

```xml
<parent>
  <groupId>de.tu-dresden.inf.lat</groupId>
  <artifactId>lat-parent</artifactId>
  <version>0.1.8</version>
  <relativePath></relativePath>
</parent>
```


## Source code

To clone the project:

```
$ git clone https://github.com/julianmendez/lat-parent.git
```

The bundles uploaded to [Sonatype][sonatype] are created with:

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

[Julian Alfredo Mendez][author]


## License

This software is distributed under the [Apache License Version 2.0][license].


## Contact

In case you need more information, please contact [julianmendez][author].

[author]: https://julianmendez.github.io
[license]: https://www.apache.org/licenses/LICENSE-2.0.txt
[maven-central]: https://search.maven.org/artifact/de.tu-dresden.inf.lat/lat-parent
[build-status]: https://github.com/julianmendez/lat-parent/actions
[central-repository]: https://repo1.maven.org/maven2/de/tu-dresden/inf/lat/lat-parent/
[sonatype]: https://oss.sonatype.org


