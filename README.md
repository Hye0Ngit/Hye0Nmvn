# yewonmvn
Maven Server

Maven/Gradle compat

## How to use (Gradle)

``build.gradle``
``` 
repositories {
	maven {
		name 'YewonMVN'
		url 'http://yewonmvn.kro.kr'
		allowInsecureProtocol = true
		metadataSources {
			artifact()
		}
	}
}
```

'''Dependency Setting for YMetalLib'''

```
dependencies {
	modImplementation "kr.kro.yewonmods:yewonmods-ymetallib:${project.ymetallib_version}"
}
```

``gradle.properties``

'''Properties Setting for YMetalLib'''

```
ymetallib_version=(type your wanted version!)
```
