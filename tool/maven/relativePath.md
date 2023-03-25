> relativePath标签主要应用于parent标签中，用于指定父pom的位置
```xml
<parent>
	<groupId>xxx</groupId>
	<artifactId>xxx</artifactId>
	<version>1.0-SNAPSHOT</version>
	<relativePath>xxx</relativePath>
</parent>
```
1. relativePath用于指定父pom.xml的相对位置，默认为 ../pom.xml
2. 如果relativePath设置一个空值 ```<relativePath/>```，将始终从仓库中获取，不从本地路径获取
3. pom.xml 查找顺序：relativePath标签配置 -> 本地仓库 -> 远程仓库