以下教程仅供学习使用，针对于IntelliJ Idea 15中的Mybatis Plugin插件。

针对于windows系统中

1、下载v2.51~v2.53中的class文件

2、进入到本地Idea插件配置目录
C:\Users\你的账户目录\.IntelliJIdea15\config\plugins\mybatis_plus\lib

3、用WinRAR打开mybatis_plus.jar

4、根据class文件的路径将mybatis_plus.jar中的class替换掉

5、重启Idea，完毕。

windows测试通过的环境：
windows 8.1 & windows 7, IntelliJ Idea 15.0.1

1、使用find命令在你的用户目录下查找mybatis_plus.jar这个文件（前提你没有更改过IntelliJ Idea的配置目录，如果更改了从根目录下查找吧，花费的时间可能会多点）
JerryMac:~ jerry-osx-m$ find ~ -name "mybatis_plus.jar"
/Users/jerry-osx-m/Library/Application Support/IntelliJIdea15/mybatis_plus/lib/mybatis_plus.jar


2、你找到了mybatis_plus.jar这个文件的位置之后，将对应版本中的com目录拷贝到mybatis_plus.jar同级目录，输入命令将com目录压缩进mybatis_plus.jar中。

jar uvf mybatis_plus.jar com

3、重启Idea，完毕。
