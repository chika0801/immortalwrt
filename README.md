地址: **192.168.10.1**<br>
用户名: **root**<br>
密码: **password**

**Redmi AX6000**
```
luci-app-filetransfer
luci-app-firewall
luci-app-mtk
luci-app-opkg
luci-app-ssr-plus
    |Include Xray
    |Include ChinaDNS-NG
luci-app-turboacc-mtk
luci-theme-argon
luci-theme-bootstrap
```

**Cetron CT3003**
```
luci-app-firewall
luci-app-opkg
luci-app-ssr-plus
    |V2ray-core Selection (Xray-core)
    |Include ChinaDNS-NG
luci-theme-argon
luci-theme-bootstrap
```

**Fastrhino R66s**
```
luci-app-cpufreq
luci-app-firewall
luci-app-opkg
luci-app-passwall
    |Include Haproxy
    |Include Hysteria
    |Include NaiveProxy
    |Include Shadowsocks Libev Server
    |Include Sing-Box
    |Include tuic-client
    |Include IPT2Socks
    |Include Xray
luci-app-ssr-plus
    |V2ray-core Selection (Xray-core)
    |Include ChinaDNS-NG
luci-app-turboacc
    |Include Flow Offload
    |Include BBR CCA
    |Include Pdnsd
luci-theme-argon
luci-theme-bootstrap
```
