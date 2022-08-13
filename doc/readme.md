# Percona XtraBackup - 文档

Percona XtraBackup 是基于 MySQL 的服务器的开源热备份实用程序，在备份期间不会锁定您的数据库。


无论是 24x7 高负载服务器还是低事务量环境，Percona XtraBackup 都旨在使备份成为一个无缝过程，而不会在生产环境中中断服务器的性能。提供商业支持合同。

Percona XtraBackup 可以从 MySQL 8.0 服务器以及 Percona Server for MySQL with XtraDB、Percona Server for MySQL 8.0 和 Percona XtraDB Cluster 8.0 上的 InnoDB、XtraDB、MyISAM 和 MyRocks 表中备份数据。

> Important
> MyRocks 存储引擎的支持是在 8.0.6 版本中添加的。
> Percona XtraBackup 8.0 不支持 TokuDB 存储引擎。

Percona XtraBackup 8.0 不支持备份在 MySQL 8.0 之前的版本、Percona Server for MySQL 或 Percona XtraDB Cluster 中创建的数据库。由于 MySQL 8.0 在数据字典、redo log 和 undo log 中引入的更改与以前的版本不兼容，因此 Percona XtraBackup 8.0 目前无法支持 8.0 之前的版本。

由于Oracle在2020年4月底发布的MySQL 8.0.20的变化，Percona XtraBackup 8.0，最高版本为8.0.11，与MySQL 8.0.20或更高版本，或基于它的Percona产品不兼容： Percona Server for MySQL 和 Percona XtraDB Cluster。

有关更多信息，请参阅 [Percona XtraBackup 8.x 和 MySQL 8.0.20](https://www.percona.com/blog/2020/04/28/percona-xtrabackup-8-x-and-mysql-8-0-20/)

有关其许多高级功能的高级概述，包括功能比较，请参阅关于 Percona XtraBackup。

- 介绍
    - 关于 Percona XtraBackup
    - Percona XtraBackup 如何工作
- 安装
    - 安装 Percona XtraBackup 8.0
        - 从存储库安装 Percona XtraBackup
        - 从二进制压缩包安装 Percona XtraBackup
        - 从源代码编译和安装
        - 在 Docker 容器中运行 Percona XtraBackup
- 先决条件
    - 需要的连接和权限
    - 配置 xtrabackup
    - 服务器版本与备份版本对比

- 备份方案
    - 完整备份
    - 增量备份
    - 压缩备份

- 用户手册
    - Percona XtraBackup 用户手册


- xbcloud 二进制
    - xbcloud 二进制文件
    - 在 Swift 中使用 xbcloud 二进制文件
    - 将 xbcloud 二进制文件与 Amazon S3 结合使用
    - 将 xbcloud 二进制文件与 MinIO 结合使用
    - 将 xbcloud 与 Google Cloud Storage 结合使用
    - Exponential Backoff 指数退避

- 教程、食谱、操作指南
    - xtrabackup 的食谱
    - 操作指南
    - 辅助指南

- 参考
    - Percona XtraBackup 8.0 发行说明
    - xtrabackup 选项参考
    - xbcrypt 二进制文件
    - xbstream 二进制文件
    - 经常问的问题
    - 词汇表
    - Percona XtraBackup 创建的文件索引
    - 商标政策
    - 版本检查

- 索引和表格
    - 索引
    - 搜索页面






