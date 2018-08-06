# fastjava-parent
不需要引用spring boot、fastjava、fastjava-maker，已集成大部分包。

**推荐**使用[fastWebsite](https://github.com/shuli495/fastWebsite)此框架，已高度集成fastjava，几乎无需配置。

## 使用
### MAVEN
```
<repositories>
	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
	</repository>
</repositories>

<dependencies>
    <dependency>
    	<groupId>com.github.shuli495</groupId>
    	<artifactId>fastjava-parent</artifactId>
    	<version>2.0.0</version>
    </dependency>
</dependencies>
```
### GRADLE
```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}

dependencies {
        compile 'com.github.shuli495:fastjava-parent:2.0.0'
}
```