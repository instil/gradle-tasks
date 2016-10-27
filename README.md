# gradle-tasks

This project incorporates a number of independent Gradle build files; each of which declares a number of useful tasks with a common theme e.g. interacting with (jOOQ)[http://www.jooq.org/].  You can import these build files into your own Gradle build to simplify common tasks.

# How to Use

You can easily access the functionality of each independent Gradle build file by copying it into your own project and using gradle's _apply_ function e.g. in your _build.gradle_ file

```groovy
    apply from: "my-project/gradle/extensions/jooq.gradle"
````
    
_Please refer to each build file's README for any additional specific configuration or usage instructions_
