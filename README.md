# maven
My maven repository

# How to use this repository
## maven
```xml
<repositories>
    <repository>
        <id>kusaanko-maven</id>
        <url>https://raw.githubusercontent.com/kusaanko/maven/master/<</url>
        <releases>
            <enabled>true</enabled>
        </releases>
    </repository>
</repositories>
```

## Gralde
```gradle
repositories {
    maven {
        url = uri("https://raw.githubusercontent.com/kusaanko/maven/master/")
    }
}
```