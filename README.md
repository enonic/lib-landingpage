# lib-landingpage

Contains a landing page content type

## Usage

To "install" this library you need to update your build.gradle file in root. Add the new dependency (after other dependencies) and make sure the Enonic repository URL is set up for maven.


### Gradle build script

```
repositories {
    maven {
        url 'http://repo.enonic.net/public'
    }
}

dependencies {
    include 'com.enonic.lib:landingpage:1.0.0'
}
```


## Compatibility

| Lib version        | XP version |
| ------------- | ------------- |
| 2.0.0 | 7.0.0 |
| 1.0.0 | 6.0.0 |
