# maven
My maven repository

# How to use this repository
## maven
```xml
<repositories>
    <repository>
        <id>kusaanko-maven</id>
        <url>https://raw.githubusercontent.com/kusaanko/maven/main/</url>
        <releases>
            <enabled>true</enabled>
        </releases>
    </repository>
</repositories>
```

## Gradle
```gradle
repositories {
    maven {
        url "https://raw.githubusercontent.com/kusaanko/maven/main/"
    }
}
```