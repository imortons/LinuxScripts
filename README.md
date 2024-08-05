# LinuxScripts
Linux自用一键脚本，集成如IP修改、Hostname修改、MosDNS安装及Ui面板安装和Singbox安装等功能，后续随使用**持续更新**，敬请关注

## 特别鸣谢
@ovpavac

@Myhero_my 

@Panicpanic 

@孔昊天

## AIO脚本
Linux综合脚本，包含基础环境设置、更新及部分软件安装、卸载。

**持续更新中**

### 功能简介
 - IP
   - 静态IP修改
   - DHCP
 - HostName
 - 基础环境设置
   - Update & Upgrade
   - 安装程序依赖
   - 设置时区为Asia/Shanghai
   - 设置NTP为ntp.aliyun.com
   - 关闭53端口监听
   - 一键安装以上所有基础设置
 - MosDNS
   - 安装Mosdns
   - 重置Mosdns缓存
   - 安装Mosdns UI
   - 卸载Mosdns
   - 一键安装Mosdns及UI面板
   - 一键卸载Mosdns及UI面板
 - Sing-box
   - 安装官方sing-box/升级
   - hysteria2 回家
   - 卸载sing-box
   - 卸载hysteria2 回家
   - 一键卸载singbox及HY2回家

---
 依赖安装程序安装的依赖有：
 * curl
 * wget
 * tar
 * gawk
 * sed
 * cron
 * unzip
 * nano
 * sudo
 * vim
 * sshfs
 * net-tools
 * nfs-common
 * bind9-host
 * adduser
 * libfontconfig1
 * musl
 * git
 * build-essential
 * libssl-dev
 * libevent-dev
 * zlib1g-dev
 * gcc-mingw-w64
---

# 下载使用
```shell
curl -o mosdns_singbox_install.sh https://raw.githubusercontent.com/feiye2021/LinuxScripts/main/AIO/Scripts/mosdns_singbox_install.sh && chmod +x mosdns_singbox_install.sh && ./mosdns_singbox_install.sh
```