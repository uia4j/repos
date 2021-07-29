# repos

Available packages:

* [comm](https://github.com/uia4j/uia-comm)
* [dao](https://github.com/uia4j/uia-dao)
* [message](https://github.com/uia4j/uia-message)
* [utils](https://github.com/uia4j/uia-utils)

Add this repository in the POM.xml

```xml
<repositories>
  <repository>
    <id>my-github</id>
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

