# dst-admin:Steam平台饥荒联机版管理后台
> 工作之余，发挥余热，弄了一个steam平台的Don't Starve Together 饥荒联机版管理后台，支持傻瓜式服务器部署，方便有兴趣折腾服务器的小伙伴可以快速的搭建服务器。

## 支持的功能
1.  支持一键启动停止地面和洞穴服务
2.  支持服务器资源监控
3.  支持饥荒房间设置以及世界和MOD设置
4.  支持存档管理，存档恢复，自动备份
5.  支持无人值守时自动更新游戏
6.  支持设置额外管理员或玩家黑名单
7.  支持饥荒运行日志查看
8.  支持上传本地存档
9.  支持远程控制台，可在管理后台踢人、回滚、重置世界

## 注意事项
1.  服务默认监听端口8080
2.  默认用户名/密码 admin/123456
3.  饥荒监听端口**10888，10998，10999**（建议开放所有端口，避免一些问题）

## docker版本部署请参考：[点击查看](https://github.com/qinming99/dst-admin/blob/master/docker/README-zh.md)

## 如果需要租赁成品服务器： [点击查看](http://download.tugos.cn/img/taobao_ad.jpg)

## TODOLIST
- [ ] 升级JDK版本到JDK17
- [ ] 升级SpringBoot版本到3.0.6
- [ ] 使用jib构建docker镜像
- [ ] 使用docker compose方式启动饥荒服务器，将steamcmd和饥荒服务器分离
- [ ] 使用github action自动构建docker镜像，自动发布到docker hub、阿里云镜像仓库，加快国内用户搭建服务器速度
- [ ] 将前端页面改为react

## 预览图

![img](https://github.com/qinming99/dst-admin/blob/master/images/image1.png)
![img](https://github.com/qinming99/dst-admin/blob/master/images/image2.png)
![img](https://github.com/qinming99/dst-admin/blob/master/images/yanshi.gif)

