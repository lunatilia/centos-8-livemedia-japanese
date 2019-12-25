# CentOS Linux 8 LiveGNOME 日本語UI kickstart

## 内容
次の CentOS 8 Liveメディア を作成するための kickstart および簡易構築スクリプトです。
1. CentOS 8 LiveGNOME 日本語UI版

## 用途
- オリジナルの専用Liveメディアなどを作成する際のベース
- HDD などを処分するとき、論理的に完全削除を行いたい場合など

## 要件
- CentOS 8またはその他RHEL8互換OSが稼働しているマシン
- root権限
- git、lorax-lmc-novirt、lorax-templates-rhel、patch、および依存パッケージがインストールされていること

## 実行例
```
# git clone https://github.com/lunatilia/centos-8-livemedia-japanese
# cd centos-8-livemedia-japanese
# ./c8live-builder centos-8-live-gnome.cfg 
```

## イメージ
- [イメージのダウンロード](https://github.com/lunatilia/centos-8-livemedia-japanese/releases/tag/1.0.0-20191226)

## ライセンス

[GNU GPLv2](https://github.com/lunatilia/centos-8-livemedia-japanese/blob/master/LICENSE) (The CentOS Projectのデフォルトライセンス)

## 参考

- lorax 28 : https://weldr.io/lorax/f28-branch/lorax.html
- Livemedia-creator- How to create and use a Live CD : https://fedoraproject.org/wiki/Livemedia-creator-_How_to_create_and_use_a_Live_CD
- centos-7-livemedia-japanese : https://github.com/lunatilia/centos-7-livemedia-japanese
