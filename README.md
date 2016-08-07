# [LAT parent](http://julianmendez.github.io/lat-parent/)
*LAT parent project*


The POM file of this project is used as parent of project parent POM files.


## Download

* [The Central Repository](https://repo1.maven.org/maven2/de/tu-dresden/inf/lat/lat-parent/)
* as dependency
```xml
<dependency>
  <groupId>de.tu-dresden.inf.lat</groupId>
  <artifactId>lat-parent</artifactId>
  <version>0.1.0</version>
</dependency>
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


## License

This software is distributed under the [Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt).


## Contact

In case you need more information, please contact @julianmendez .

