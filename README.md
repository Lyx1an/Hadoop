# Hadoop
### 一键脚本启动

如果配置了`etc/hadoop/workers`和`ssh免密登录`，则可以使用程序脚本启动所有Hadoop两个集群的相关进程，在主节点所设定的机器上执行。

<span style="color:red;font-weight:bold;font-size:20px">hdfs：/bigdata/server/hadoop/sbin/start-dfs.sh</span>

<span style="color:red;font-weight:bold;font-size:20px">yarn：/bigdata/server/hadoop/sbin/start-yarn.sh</span>

> 停止脚本
>
> hdfs：/bigdata/server/hadoop/sbin/stop-dfs.sh
>
> yarn：/bigdata/server/hadoop/sbin/stop-yarn.sh



> 完整的一键启动hdfs和yarn脚本
>
> start-all.sh: 启动所有的hdfs和yarn的脚本
>
> stop-all.sh: 停止所有的hdfs和yarn的脚本

## 启动hive 与外部idea客户端连接
> hive --service hiveserver2 &
