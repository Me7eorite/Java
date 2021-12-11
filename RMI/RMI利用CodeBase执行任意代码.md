## Applet

Java 在以前的一段时间中可以直接运行在浏览器中，需要指定一个codebase属性。

- codebase是一个地址，告诉JVM应该去那里获取这个类。主要的参数是http、或者是ftp
- 类似于CLASSPATH不过区别在于这个是搜索和获取本地的类

```js
<applet code="HelloWorld.class" codebase="Applets" width="800" height="600">
</applet>
```

