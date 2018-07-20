# hadoop

运行主函数为senddata;

数据库地址:
/dbMaster/DBhelper/url：192.168.119.207:3306；
HDFS址：
/interactionWithHadoop/HadoopOpt/init/:192.168.119.200:9000;

在运行时，将代码17处galname更改为自己要上传的gif所在的文件夹中即可。


error：
1.文件地址错误：查看galname是否存在不能到达、大小写出错的问题；
2.db连接错误:通过navicat等工具检查db是否可达；
3.hadoop连接错误：检查hadoop地址是否被更改；
