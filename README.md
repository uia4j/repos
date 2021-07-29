# repos
## Packages
The group id of all packages is `org.uia.solution`, and avilable artifacts are

* [uia-comm](https://github.com/uia4j/uia-comm)
* [uia-dao](https://github.com/uia4j/uia-dao)
* [uia-message](https://github.com/uia4j/uia-message)
* [uia-utils](https://github.com/uia4j/uia-utils)

## Configuration

Setup __settings.xml__ and project's __pom.xml__ to download packages from this repository.

Note: you can change the keyword `github-g2k-download` to any what you like. 

* settings.xml

```xml
<server>
  <id>github-g2k-download</id>
  <username>gazer2kanlin</username>
  <password>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</password>
</server>

```

* POM.xml

```xml
<repositories>
  <repository>
    <id>github-g2k-download</id>
    <url>https://maven.pkg.github.com/uia4j/repos</url>
    <snapshots>
      <enabled>true</enabled>
    </snapshots>
    <releases>
      <enabled>true</enabled>
    </releases>  
  </repository>
</repositories>
```

