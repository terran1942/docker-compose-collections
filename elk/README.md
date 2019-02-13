# ELK Stack + Filebeat
ELK集中式日志分析，采用Filebeat采集日志。

使用docker-compose启动
``` shell
docker-compose up
```
elasticsearch为映射目录，将需要处理的日志放置于logs目录下即可，日志文件匹配*.log，建议使用IOS8601时间戳格式。