# 日志切割备份

## 简介 

日志文件随着时间推移会变大并占用越来多越的磁盘空间。
BEF内置日志自动切割及备份功能，可定期切割日志，删除并仅保留最近的日志文件。

## 配置

| 日志名称    |  日志路径      | 日志切割及备份配置                |
| ----------- | -------------- | --------------------------------- |
| server log  | log/bfe.log    | 按天切隔日志，保留最近7天日志     |
| access log  | log/access.log | 见[conf/mod_access/mod_access.conf](../configuration/mod_access/mod_access.md) |
| tls key log | log/key.log    | 见[conf/mod_key_log/mod_key_log.conf](../configuration/mod_key_log/mod_key_log.md) |
