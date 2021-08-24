# ffty-dependencies-parent  
## pom.xml 依赖配置  
```xml 
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.ffty</groupId>
            <artifactId>ffty-dependencies-parent</artifactId>
            <version>${dep.version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```