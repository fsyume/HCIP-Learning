# OSPF

## 简介

Open Shortest Path First（开放式最短路径优先）是一个基于链路状态的内部网关协议（Interior Gateway Protocol，IGP）

IPv4协议使用的是OSPF Version 2（RFC 2328）

IPv6协议使用的是OSPF Version 3（RFC 2740）

## OSPF基本配置实验

### 单区域OSPF配置

R1配置命令：

```
<Huawei>system-view  //进入系统视图
Enter system view, return user view with Ctrl+Z.
[Huawei]undo info-center enable 
[Huawei]sysname R1
[R1]interface g0/0/0
[R1-GigabitEthernet0/0/0]ip address 12.1.1.1 24
[R1-GigabitEthernet0/0/0]quit
[R1]interface LoopBack 0
[R1-LoopBack0]ip address 1.1.1.1 24
[R1-LoopBack0]quit
```





