# SysId: System Identification for Robot Mechanisms

This is the C++ version of [frc-characterization](https://github.com/wpilibsuite/frc-characterization). It uses the [wpimath](https://github.com/wpilibsuite/allwpilib/tree/main/wpimath) backend for generating feedforward and feedback gains.

## Building and Running SysId

SysId uses Gradle to build. To build debug and release versions of the main executable and run tests, run `./gradlew build`. During development, you can use `./gradlew run` to build and run the debug executable.

### Requirements

- [JDK 11](https://adoptopenjdk.net/)
    - Note that the JRE is insufficient; the full JDK is required
    - On Ubuntu, run `sudo apt install openjdk-11-jdk`
    - On Windows, install the JDK 11 .msi from the link above
    - On macOS, install the JDK 11 .pkg from the link above
- C++ compiler
    - On Linux, install GCC 7 or greater
    - On Windows, install [Visual Studio Community 2019](https://visualstudio.microsoft.com/vs/community/) and select the C++ programming language during installation (Gradle can't use the build tools for Visual Studio 2019)
    - On macOS, install the Xcode command-line build tools via `xcode-select --install`
