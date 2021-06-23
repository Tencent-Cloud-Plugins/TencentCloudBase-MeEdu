<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [MeEdu](https://github.com/Qsnh/meedu)

MeEdu是一款免费在线教育点播系统，支持视频点播、电子书、图文收费、考试系统、问答、学习路径、视频试看等功能。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-MeEdu&branch=master)
### 配置
- `DB_HOST`：meedu 数据库地址
- `DB_PORT`：meedu 数据库端口
- `DB_USER`: 客户端创建的数据库账号
- `DB_PASS`: 客户端创建的数据库账号密码
- `DB_NAME`：meedu 数据库名

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
