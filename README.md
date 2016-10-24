# mvn publish test

> Testing how to build and publish a java project.

The best way of distributing a Java library is releasing a jar and uploading it to GitHub as a release.
#
1. Package jar
2. Upload jar
3. Use jar in different project

# How to package a jar (for external developers)
- 1. `mvn package`
- 2. Put `.jar` in GitHub `releases`
  - `https://github.com/grant/mvn-publish-test/releases`

# How to upload a jar
- Go to your GitHub repo (https://github.com/grant/mvn-publish-test/releases)
- Add the jar to a release

# How to run jar
- Remove library: `rm -rf target`
- Package library: `mvn package`
- Run main method of `App`: `java -cp target/mvn-publish-test-0.0.1-SNAPSHOT.jar cm.grant.App`

# How to use the jar from a different project
- https://github.com/grant/mvn-publish-usage
