# v2rayNG

A V2Ray client for Android, support [Xray core](https://github.com/XTLS/Xray-core) and [v2fly core](https://github.com/v2fly/v2ray-core)

[![API](https://img.shields.io/badge/API-21%2B-yellow.svg?style=flat)](https://developer.android.com/about/versions/lollipop)
[![Kotlin Version](https://img.shields.io/badge/Kotlin-2.1.21-blue.svg)](https://kotlinlang.org)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/2dust/v2rayNG)](https://github.com/2dust/v2rayNG/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/2dust/v2rayng/badge)](https://www.codefactor.io/repository/github/2dust/v2rayng)
[![GitHub Releases](https://img.shields.io/github/downloads/2dust/v2rayNG/latest/total?logo=github)](https://github.com/2dust/v2rayNG/releases)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/v2rayn)


### Usage

#### Geoip and Geosite
- geoip.dat and geosite.dat files are in `Android/data/com.v2ray.ang/files/assets` (path may differ on some Android device)
- download feature will get enhanced version in this [repo](https://github.com/Loyalsoldier/v2ray-rules-dat) (Note it need a working proxy)
- latest official [domain list](https://github.com/Loyalsoldier/v2ray-rules-dat) and [ip list](https://github.com/Loyalsoldier/geoip) can be imported manually
- possible to use third party dat file in the same folder, like [h2y](https://guide.v2fly.org/routing/sitedata.html#%E5%A4%96%E7%BD%AE%E7%9A%84%E5%9F%9F%E5%90%8D%E6%96%87%E4%BB%B6)

### Development guide

Android project under V2rayNG folder can be compiled directly in Android Studio, or using Gradle wrapper. But the v2ray core inside the aar is (probably) outdated.  
The aar can be compiled from the Golang project [AndroidLibV2rayLite](https://github.com/2dust/AndroidLibV2rayLite) or [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite).
For a quick start, read guide for [Go Mobile](https://github.com/golang/go/wiki/Mobile) and [Makefiles for Go Developers](https://tutorialedge.net/golang/makefiles-for-go-developers/)

v2rayNG can run on Android Emulators. For WSA, VPN permission need to be granted via
`appops set [package name] ACTIVATE_VPN allow`

## OTHER GUI Clients

- OpenWrt
  - [PassWall](https://github.com/xiaorouji/openwrt-passwall), [PassWall 2](https://github.com/xiaorouji/openwrt-passwall2)
  - [ShadowSocksR Plus+](https://github.com/fw876/helloworld)
  - [luci-app-xray](https://github.com/yichya/luci-app-xray) ([openwrt-xray](https://github.com/yichya/openwrt-xray))
- Asuswrt-Merlin
  - [XRAYUI](https://github.com/DanielLavrushin/asuswrt-merlin-xrayui)
- Windows
  - [v2rayN](https://github.com/2dust/v2rayN)
  - [Furious](https://github.com/LorenEteval/Furious)
  - [Invisible Man - Xray](https://github.com/InvisibleManVPN/InvisibleMan-XRayClient)
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG)
  - [X-flutter](https://github.com/XTLS/X-flutter)
  - [SaeedDev94/Xray](https://github.com/SaeedDev94/Xray)
- iOS & macOS arm64
  - [Happ](https://apps.apple.com/app/happ-proxy-utility/id6504287215)
  - [Streisand](https://apps.apple.com/app/streisand/id6450534064)
  - [OneXray](https://github.com/OneXray/OneXray)
- macOS arm64 & x64
  - [V2rayU](https://github.com/yanue/V2rayU)
  - [V2RayXS](https://github.com/tzmax/V2RayXS)
  - [Furious](https://github.com/LorenEteval/Furious)
  - [OneXray](https://github.com/OneXray/OneXray)
- Linux
  - [v2rayA](https://github.com/v2rayA/v2rayA)
  - [Furious](https://github.com/LorenEteval/Furious)

## Others that support VLESS, XTLS, REALITY, XUDP, PLUX...

- iOS & macOS arm64
  - [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118)
  - [Loon](https://apps.apple.com/us/app/loon/id1373567447)
- Xray Tools
  - [xray-knife](https://github.com/lilendian0x00/xray-knife)
  - [xray-checker](https://github.com/kutovoys/xray-checker)
- Xray Wrapper
  - [XTLS/libXray](https://github.com/XTLS/libXray)
  - [xtlsapi](https://github.com/hiddify/xtlsapi)
  - [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite)
  - [Xray-core-python](https://github.com/LorenEteval/Xray-core-python)
  - [xray-api](https://github.com/XVGuardian/xray-api)
- [XrayR](https://github.com/XrayR-project/XrayR)
  - [XrayR-release](https://github.com/XrayR-project/XrayR-release)
  - [XrayR-V2Board](https://github.com/missuo/XrayR-V2Board)
- Cores
  - [mihomo](https://github.com/MetaCubeX/mihomo)
  - [sing-box](https://github.com/SagerNet/sing-box)

  
### Forked from https://github.com/2dust/v2rayNG
