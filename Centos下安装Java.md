1.JDK下载 [oracle](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

![](http://images.monsterlin.com//github/java.png)

2. 解压
3. 配置环境变量
```
vim /etc/profile


export JAVA_HOME=/home/softwares/jdk/jdk1.8.0_91  
export PATH=$JAVA_HOME/bin:$PATH  
export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar  
```

4. 执行命令：source /etc/profile，使修改的环境变量生效。
5. 输出环境变量，查看是否有（5）中的路径:echo $PATH
6. 检测安装是否成功:java -version:
7. OK
