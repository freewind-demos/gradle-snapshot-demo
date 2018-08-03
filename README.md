在Gradle中把当前项目声明为SNAPSHOT并发布到本地
==============================

有时候为了方便开发，我们想把一个项目声明为SNAPSHOT并且只在本机使用。

做法很简单，就是在version后面加一个`-SNAPSHOT`即可，然后发布到本机：

```
./gradlew install
```
