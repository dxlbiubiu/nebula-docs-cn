# 更新配置

在更新配置页面，用户可以修改 Storage 及 Graph 服务的配置文件。

## 入口

1. 在 Dashboard 企业版顶部导航栏，单击**集群管理**。
2. 单击目标集群右侧**详情**。
3. 在左侧导航栏，单击**集群操作**->**更新配置**。

## 操作说明

单击**编辑**修改配置并**确认**，然后在右上角单击**保存**或**保存并重启**。

- **保存**：在下一次服务重启后配置才生效。

- **保存并重启**：直接自动重启服务使配置立即生效。

  !!! danger

        单击**保存并重启**，会立即中断进行中的任务重启集群，可能会导致数据不一致，请在业务低峰期执行该操作。

  !!! note

      - 更新配置文件为批量操作，将会修改每一个 Storage/Graph 的配置文件。
      - 配置参数说明参见 [Storage 服务配置](../../../5.configurations-and-logs/1.configurations/4.storage-config.md)和 [Graph 服务配置](../../../5.configurations-and-logs/1.configurations/3.graph-config.md)。