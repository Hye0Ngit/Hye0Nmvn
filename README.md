# yewonmvn
Maven Server

Maven/Gradle compat

## Directory Listing
[here](https://www.yewonmvn.kro.kr/DIR)

## How to use (Gradle)

``build.gradle``
``` 
repositories {
	maven {
		name 'YewonMVN'
		url 'https://www.yewonmvn.kro.kr'
		metadataSources {
			artifact()
		}
	}
}
```

**Dependency Setting for YMetalLib**

```
dependencies {
	modImplementation "kr.kro.yewonmods:yewonmods-ymetallib:${project.ymetallib_version}"
}
```

``gradle.properties``

**Properties Setting for YMetalLib**

```
ymetallib_version=(type your wanted version!)
```
