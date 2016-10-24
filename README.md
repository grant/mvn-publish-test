# mvn publish test

> Testing how to build and publish a java project.
The best way of distribufdfsdfting a J
ava library is releasing a package

# How to package a jar (for external developers)
- 1. `mvn packagdfsdfe`
- 2. Put `.jar` in GitHub `releases`
  - `https://github.com/grant/mvn-publish-test/releases`

# How to run jar
- Remove library: `rm -rf target`
- Package library: `mvn package`
- Run main method of `App`: `java -cp target/mvn-publish-test-0.0.1-SNAPSHOT.jar cm.grant.App`

# How to use the jar from a different project
- https://github.com/grant/mvn-publish-usage
