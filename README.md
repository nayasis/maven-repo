## maven snapshot repository

### maven

add repository in **pom.xml**.

```xml
<repositories>
  <repository>
    <id>nayasis-maven-repo</id>
    <url>https://raw.github.com/nayasis/maven-repo/mvn-repo</url>
  </repository>
</repositories>
```

### gradle

add repository in **build.gradle.kts**.

```kotlin
repositories {
  maven { url = uri("https://raw.github.com/nayasis/maven-repo/mvn-repo") }
}
```
