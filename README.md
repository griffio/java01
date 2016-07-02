# Base Java 8 Project

For cloning and extending in basic projects  

## Gradle Dependencies

~~~ groovy
dependencies {

  compile(
    "com.google.code.findbugs:jsr305:${jsr305_version}",
    "org.slf4j:slf4j-api:${slf4j_api_version}",
    "ch.qos.logback:logback-classic:${logback_version}"
  )

  testCompile(
    "org.testng:testng:${testng_version}",
    "com.google.truth:truth:${truth_version}",
    "com.google.guava:guava-testlib:${guava_version}"
  )
}
~~~
