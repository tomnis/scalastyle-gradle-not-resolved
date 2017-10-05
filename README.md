# scalastyle-gradle-not-resolved

gradle-scalastyle-plugin_2.12:1.0.0 is not resolvable from jcenter

```
» ./gradlew scalaStyle

FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring root project 'scalastyle-gradle-not-resolved'.
> Could not resolve all files for configuration ':classpath'.
   > Could not find org.github.ngbinh.scalastyle:gradle-scalastyle-plugin_2.12:1.0.0.
     Searched in the following locations:
         https://jcenter.bintray.com/org/github/ngbinh/scalastyle/gradle-scalastyle-plugin_2.12/1.0.0/gradle-scalastyle-plugin_2.12-1.0.0.pom
         https://jcenter.bintray.com/org/github/ngbinh/scalastyle/gradle-scalastyle-plugin_2.12/1.0.0/gradle-scalastyle-plugin_2.12-1.0.0.jar
     Required by:
         project :

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

* Get more help at https://help.gradle.org

BUILD FAILED in 1s
```
