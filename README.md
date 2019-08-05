# skip_maven_tests
How to skip test in a maven project

In case one needs to skip the unit tests for a maven project, for any given reason, maven.test.skip is the property that needs to be set to true.

*this will package the project and trigger the tests*

**mvn package**



*this will package the project and skip the tests*

**mvn package -PskipTestProfile**
