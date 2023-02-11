

<div align="center"> 

<h1 align="center">

GitHub Actions For 360T7 OpenWrt

</h1>

[![GitHub Stars](https://img.shields.io/github/stars/hkk666/360T7?style=flat-square)](https://github.com/hkk666/360T7/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/hkk666/360T7?style=flat-square)](https://github.com/hkk666/360T7/network)
[![GitHub Issues](https://img.shields.io/github/issues/hkk666/360T7?style=flat-square)](https://github.com/hkk666/360T7/issues)
[![GitHub Contributors](https://img.shields.io/github/contributors/hkk666/360T7?style=flat-square)](https://github.com/hkk666/360T7/graphs/contributors)
[![GitHub All Releases](https://img.shields.io/github/downloads/hkk666/360T7/total?style=flat-square)](https://github.com/hkk666/360T7/releases)
[![GitHub License](https://img.shields.io/github/license/hkk666/360T7?style=flat-square)](https://github.com/hkk666/360T7/blob/main/LICENSE)
![GitHub Release (latest SemVer)](https://img.shields.io/github/v/release/hkk666/360T7?style=flat-square)

</div>

![openwrt](doc/img/openwrt.png)

## 友情提醒
此仓库只是拉取源码进行编译，本人并不会修复相关问题！
如果你遇到问题，可以提issues，我会尽力帮助你.

## 目录介绍

```tree
360T7
├── .github/workflows
│   ├── 360T7-hanwckf-mini.yml        云编译 360T7
│   ├── update-checker.yml            定时检查源码更新
├── doc
│   ├── backup                        旧文件备份
│   ├── config
│   │   ├──360T7-hanwckf-mini.config  固件定制
│   │   ├──ua2f.config                ua2f依赖
│   ├── diy                           自定义脚本文件
│   ├── img                           图片存放
├── LICENSE
└── README.md
```

## 食用教程

### 1.Fork本仓库

### 2.前往 [Settings/Developer settings](https://github.com/settings/tokens/new) 创建 `GIT_USER_TOKEN` `GITHUB_TOKEN` 密钥,如果你需要定时检查源码并自动触发编译，还需要创建 `ACTIONS_TRIGGER_PAT` 密钥.密钥创建页面,填入名称,Expiration选择 `no expiration` ,Select scopes选择`workflows` `admin:repo_hook`.
实例图示：

![示例](doc/img/example1.png)

## 特别鸣谢

|          [lean](https://github.com/coolsnowwolf/lede)         |        [天灵](https://github.com/1715173329)               |              [lorz](https://github.com/1orz/My-action)               |              [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)               |          [Zxilly](https://github.com/Zxilly/UA2F)         |           [dawidd6](https://github.com/dawidd6/action-send-mail)          |              [stupidloud](https://github.com/stupidloud/cachewrtbuild)               |              [hanwckf](https://github.com/hanwckf/immortalwrt-mt798x)               |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| <img width="60" src="https://avatars.githubusercontent.com/u/31687149?v=4"/> | <img width="60" src="https://avatars.githubusercontent.com/u/22235437?v=4" /> | <img width="60" src="https://avatars.githubusercontent.com/u/31647663?v=4" /> | <img width="60" src="https://avatars.githubusercontent.com/u/25927179?v=4" /> | <img width="60" src="https://avatars.githubusercontent.com/u/31370133?v=4"/> | <img width="60" src="https://avatars.githubusercontent.com/u/9713907?v=4" /> | <img width="60" src="https://avatars.githubusercontent.com/u/56048681?v=4" /> | <img width="60" src="https://avatars.githubusercontent.com/u/27666983?v=4" /> |

