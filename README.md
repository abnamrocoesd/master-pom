# master-pom to be used by all ABN Amro shared libraries

This pom contains all the necessaary plugins required to share an OSS library to maven-central.
It also enforces some quality control which is as per ABN coding standards.

**Maven:**

```xml
<parent>
    <groupId>com.abnamro.coesd.public</groupId>
    <artifactId>master-pom</artifactId>
    <version>2.0.0</version>
</parent>
```
