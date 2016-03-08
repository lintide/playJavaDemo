## 环境

操作系统： `OS X 10.11.3`

安装 `activator`

```
$ brew install typesafe-activator
```

## 创建项目

```
$ activator new playJavaDemo play-java
```

本示例使用 __java__ 作为开发语言，如果要使用 __scala__ 开发，则用`play-scala` 代替 `play-java` 即可。

## 运行

```
$ cd playJavaDemo
$ activator run
```

等待安装所有依赖吧...

## 验证运行结果

```
$ http http://localhost:9000/
```

## 参考
[Play Docs](https://www.playframework.com/documentation/2.5.x/Home)

[Play 项目目录结构](https://www.playframework.com/documentation/2.0/Anatomy)
