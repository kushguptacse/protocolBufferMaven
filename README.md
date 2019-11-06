# Protocol buffer project to generate java class from proto file

Steps - <br />
1. add dependency and build plugin in pom.xml to support proto3.<br />
2. After importing project.<br />
3. mvn clean install protobuf:compile.<br />
4.it will generate java classes under target\generated-sources\protobuf\java
5.now client application can take this model and start using it.
