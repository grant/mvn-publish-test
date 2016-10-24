# mvn publish test

Testing how to build and publish a java project.

The best way of distributing a Java library is releasing a package

# How to package
- `mvn package`
= Put JAR in GitHub `releases`
  - `https://github.com/grant/mvn-publish-test/releases`

# How to run
- `rm -rf target`
- `mvn package`
- `java -cp target/mvn-publish-test-0.0.1-SNAPSHOT.jar cm.grant.App`


