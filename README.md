# Akane313.2

寝室路由器的状态节点 <https://509.qfstudio.net>

使用的技术为Shell和PHP。

## 安装

```sh
git clone https://github.com/gzhu-team-509/Carrier9-mod-monit
```

如果Openwrt平台不支持git：

```sh
wget -c https://github.com/gzhu-team-509/Carrier9-mod-monit/archive/master.zip -O carrier9.zip
unzip -o carrier9.zip
rm carrier9.zip
```

## 配置

```sh
# cd path-to-Carrier9-mod-monit
cp router/key.example router/host.example
cp server/config.example.php server/config.php
vi router/host       # 设置server端的HTTP位置
vi router/key        # 设置key
vi server/config.php # 设置key为与router/key相同
```
