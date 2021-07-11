# 介绍

Trojan Panel一键安装脚本

# 环境要求

## 系统要求

系统支持: CentOS 7

内存要求: ≥1G

## 开放端口

数据库版开放以下端口: 80 443 8863 3306 8888

单机版开放以下端口: 80 443 8863

# 一键安装脚本

```shell
yum install -y wget;wget --no-check-certificate https://github.com/trojanpanel/install-script/raw/main/install_script.sh;chmod 777 install_script.sh;./install_script.sh
```

# 说明

1. 以数据库版为例,建议的安装顺序: 卸载云盾(阿里云服务器) > 安装加速 > 安装面板 > 安装节点

# 客户端推荐

- Android: [igniter](https://github.com/trojan-gfw/igniter)
- IOS: [Shadowrocket-GFW](https://apps.apple.com/us/app/shadowrocket/id932747118)
- Windows: [Qv2ray](https://github.com/Qv2ray/Qv2ray/) & [QvPlugin-Trojan](https://github.com/Qv2ray/QvPlugin-Trojan)

# 交流

Telegram: [trojanpanel](https://t.me/trojanpanel)