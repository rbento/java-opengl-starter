# java-opengl-starter

A minimal template for OpenGL projects with Java and Maven.

### Dependencies
---

- [Java 16][1]
- [Maven][2]
- [LWJGL][3]
- [WiX Toolset][4] (Required to generate an application installer with jpackage on Windows)

### Generate Installer
---

```
$ jpackage --input ./ --main-class Main --main-jar java-opengl-minimal-1.0.0.jar
```

[1]:https://adoptopenjdk.net/?variant=openjdk16&jvmVariant=hotspot
[2]:https://maven.apache.org
[3]:https://www.lwjgl.org/
[4]:https://wixtoolset.org/ 
