# gradle-sample

## How to Build Gradle-Sample

### Requirements

- Java >= 1.7
- Internet connection (dependencies are downloaded automatically)
- IDE: [Gradle](http://www.gradle.org/) Plugin (not necessary for command line usage)

### IDE

Open the `gradle-sample` project in your favourite IDE (tested with NetBeans 8 and IntelliJ 14) and build it by calling the `assemble` task.

### Command Line

Navigate to the [Gradle](http://www.gradle.org/) project (e.g., `path/to/gradle-sample`) and enter the following command

#### Bash (Linux/OS X/Cygwin/other Unix-like shell)

    sh gradlew assemble
    
#### Windows (CMD)

    gradlew assemble
  
## How to Run Gradle-Sample

Call the `run` task (e.g. `sh gradlew run`).

### Expected output:

```
Downloading http://services.gradle.org/distributions/gradle-2.2-bin.zip
............................................................................
Unzipping /home/demouser/.gradle/wrapper/dists/gradle-2.2-bin/1qpl4qfgl1m63bs47m4bicq4n2/gradle-2.2-bin.zip to /home/demouser/.gradle/wrapper/dists/gradle-2.2-bin/1qpl4qfgl1m63bs47m4bicq4n2
Set executable permissions for: /home/demouser/.gradle/wrapper/dists/gradle-2.2-bin/1qpl4qfgl1m63bs47m4bicq4n2/gradle-2.2/bin/gradle
:compileJava
:processResources UP-TO-DATE
:classes
:run
Yes, Gradle works :-)
```
