## dandar3 / platform_dalvik

`aosp-mirror/platform_dalvik` fork with the aim of making the tools compatible with Google ADT plugin for Eclipse again.

### How to build (dx.jar)
```
cd dx
mvn clean package
copy "target\dx-1.16-ADT.jar" "%ANDROID_HOME%\build-tools\25.0.3\lib\dx.jar*"
```