此项目是Tomcat7.0.73源码分析项目

# 1. 导入IDE

使用Intellij Idea 导入maven项目即可。

# 2. 启动

设置VM参数：

```
-Dcatalina.home=catalina-home
-Dcatalina.base=catalina-home
-Djava.endorsed.dirs=catalina-home/endorsed
-Djava.io.tmpdir=catalina-home/temp
-Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager
-Djava.util.logging.config.file=catalina-home/conf/logging.properties
```
