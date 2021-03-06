# Downloads

The [latest version of parquet-format is 2.7.0](https://www.apache.org/dyn/closer.lua/parquet/apache-parquet-format-2.7.0/apache-parquet-format-2.7.0.tar.gz).

To [check the validity](https://www.apache.org/info/verification.html) of this release, use its:

 * [Release manager OpenPGP key](https://www.apache.org/dist/parquet/KEYS)
 * [OpenPGP signature](https://www.apache.org/dist/parquet/apache-parquet-format-2.7.0/apache-parquet-format-2.7.0.tar.gz.asc)
 * [SHA-512](https://www.apache.org/dist/parquet/apache-parquet-format-2.7.0/apache-parquet-format-2.7.0.tar.gz.sha512)

### Downloading from the Maven central repository

The Parquet team publishes its [releases to Maven Central](https://search.maven.org/search?q=g:org.apache.parquet).

Add the following dependency section to your pom.xml:

	<dependencies>
	...
	   <dependency>
          <groupId>org.apache.parquet</groupId>
          <artifactId>parquet-avro</artifactId>
          <version>1.10.1</version> <!-- or latest version -->
       </dependency>
    ...
    </dependencies>

### Older Releases

Older releases can be found in the Archives of the Apache Software Foundation:
[https://archive.apache.org/dist/parquet/](https://archive.apache.org/dist/parquet/)
