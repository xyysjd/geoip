# 简介

本项目每天早上七点二十自动生成 GeoIP 文件，包括但不限于 V2Ray dat 格式文件 `geoip.dat`、 MaxMind mmdb 格式文件 `Country.mmdb`、sing-box db格式文件 `geoip.db` 以及 Clash.Meta metadb格式文件 `geoip.metadb`。

## 与官方版 GeoIP 的区别

- 中国 IPv4地址数据使用 [misakaio/chnroutes2](https://github.com/misakaio/chnroutes2)。
- 中国 IPv6地址数据使用 [ChanthMiao/China-IPv6-List](https://github.com/ChanthMiao/China-IPv6-List)
- 新增类别（方便有特殊需求的用户使用）：
  - `geoip:bilibili`（`GEOIP,BILIBILI`）
  - `geoip:cloudflare`（`GEOIP,CLOUDFLARE`）
  - `geoip:google`（`GEOIP,GOOGLE`）
  - `geoip:netflix`（`GEOIP,NETFLIX`）
  - `geoip:telegram`（`GEOIP,TELEGRAM`）
  - `geoip:twitter`（`GEOIP,TWITTER`）
  - `geoip:wechat`（`GEOIP,WECHAT`）

## 下载地址

### V2Ray dat 格式路由规则文件

> 适用于 [V2Ray](https://github.com/v2fly/v2ray-core)、[Xray-core](https://github.com/XTLS/Xray-core) 和 [Trojan-Go](https://github.com/p4gefau1t/trojan-go)。

- **geoip.dat**：
  - [https://github.com/d2184/geoip/raw/release/geoip.dat](https://github.com/d2184/geoip/raw/release/geoip.dat)

- **geoip-lite.dat (only cn and private)**:
  - [https://github.com/d2184/geoip/raw/release/geoip-lite.dat](https://github.com/d2184/geoip/raw/release/geoip-lite.dat)

### MaxMind mmdb 格式文件

> 适用于 [Clash](https://github.com/Dreamacro/clash) 和 [Leaf](https://github.com/eycorsican/leaf)。

- **Country.mmdb**：
  - [https://github.com/d2184/geoip/raw/release/Country.mmdb](https://github.com/d2184/geoip/raw/release/Country.mmdb)

- **Country-lite.mmdb (only cn and private)**:
  - [https://github.com/d2184/geoip/raw/release/Country-lite.mmdb](https://github.com/d2184/geoip/raw/release/Country-lite.mmdb)

### sing-box db 格式文件

> 适用于 [sing-box](https://github.com/SagerNet/sing-box)。

- **geoip.db**：
  - [https://github.com/d2184/geoip/raw/release/geoip.db](https://github.com/d2184/geoip/raw/release/geoip.db)

- **geoip-lite.db (only cn and private)**:
  - [https://github.com/d2184/geoip/raw/release/geoip-lite.db](https://github.com/d2184/geoip/raw/release/geoip-lite.db)

### Clash.Meta metadb 格式文件

> 适用于 [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta)。

- **geoip.metadb**：
  - [https://github.com/d2184/geoip/raw/release/geoip.metadb](https://github.com/d2184/geoip/raw/release/geoip.metadb)

- **geoip-lite.metadb (only cn and private)**:
  - [https://github.com/d2184/geoip/raw/release/geoip-lite.metadb](https://github.com/d2184/geoip/raw/release/geoip-lite.metadb)

## 注意

由于本项目使用的均为免费数据，在精度上难免存在偏差，如有精准IP定位需求，请自行前往 [ipip.net](https://ipip.net) 等BGP/ASN数据分析服务商购买付费服务。

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
