# stage-lib-gradle-template
Gradle template for building a new stage library for StreamSets Data Collector

Includes Java plugin by default. Add your code to `src/main/java` and modify the project name in `settings.gradle` and
`datacollector-library-bundle-properties` accordingly.

`./gradlew clean distTar` will generate a tarball bundle that can be extracted into SDC's user-libs or streamsets-libs directories.
