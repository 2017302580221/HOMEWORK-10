# 网络分布式 第十次作业

[TOC]

## P14

### a.

eBGP。因为路由器3c只能从路由器4c中学习到前缀x，所以要经由外部BGP连接，即eBGP。

### b.

iBGP。因为路由器3a可以通过内部BGP获取到相同AS中其他路由器学习到前缀x，因而为iBGP。

### c. 

eBGP。因为路由器1a需要从路由器3a中学习到前缀x，所以需要通过外部BGP连接，即eBGP。

### d.

iBGP。因为路由器1d可以通过内部BGP获取到相同AS中其他路由器学习到前缀x，因而为iBGP。

## P15

### a.

I等于I1，因为I1接口指引了路由器1d到网关路由器1c的最短路径。

### b.

I等于I2，虽然两种接口有相同的AS-PATH，但是I2接口指令的从路由器1d到网关路由器1b路径的代价更小。

### c.

I等于I1，因为接口I1指引的路径的AS-PATH更小。

## P19

A对B的建议有两条路线，A-W和A-V。

A对C的建议有一条路线，A-V。

C作为路径接收：B-A-W、B-A-V、A-V。