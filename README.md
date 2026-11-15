<!-- SPDX-FileCopyrightText: 2026 Progmasoft <support@progmasoft.com> -->
<!-- SPDX-License-Identifier: MIT -->

# JAriane

JAriane brings the diagnostics of [Ariane](https://github.com/Progmasoft/ariane) to Java: reports drawn over the source
code they are about, with labels, notes and helps, by the Rust library Ariadne behind Ariane's C API.

It is for Java 21 and later, and for the JVM 21+ languages that call Java libraries, such as Kotlin, Scala and Groovy.
It reaches Ariane's C API through JNI. Its builds are published to the Maven repository of Progmasoft:

```kotlin
repositories {
    maven("https://maven.progmasoft.com/wrapper")
}

dependencies {
    implementation("com.progmasoft.jariane:jariane-jni:$jarianeVersion")
}
```

No code is written yet; the first version of JAriane follows the first release of Ariane.

## The Ariane family

| Repository | For |
| --- | --- |
| [Progmasoft/ariane](https://github.com/Progmasoft/ariane), Ariane | C, through its C API |
| [Progmasoft/arianex](https://github.com/Progmasoft/arianex), Arianex | C++17 |
| [Progmasoft/jariane](https://github.com/Progmasoft/jariane), JAriane | Java 21+ and the JVM 21+ languages with Java interop |
| [Progmasoft/arianekt](https://github.com/Progmasoft/arianekt), ArianeKt | Kotlin/JVM 25+ |
| [Progmasoft/ariane.net](https://github.com/Progmasoft/ariane.net), Ariane.NET | the .NET 8+ languages |

## License

[MIT](LICENSE.txt). Progmasoft's own code is also covered by the [Progmasoft Patent Grant 1.1](PATENTS.md).
Participation follows the [Code of Conduct](CODE_OF_CONDUCT.md).
