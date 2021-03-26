# FMEを用いたIFCからCityGMLへの変換フォーマット
# 概要
FMEによるIFCデータからCityGMLデータへの変換フォーマットです。
本ソフトウェアは、国土交通省の[Project PLATEAU](https://www.mlit.go.jp/plateau/)で利用したものです。

## 前提ソフトウェア

前提ソフトウェア
・商用ソフトウェア：[FME Desktop](https://www.safe.com/fme/fme-desktop/)

### 利用方法

* 上記の前提ソフトウェアをインストールします。
* 本レポジトリの一式をダウンロードし、任意のディレクトリに置きます。
* FME Workbenchで本ファイルを開いて実行
* 変換元の建物ファイル(IFC)と各ファイルの読み込み
* 変換確認 ”Run” と保存

### モデル変換後の確認

* 確認1. 変換後モデルチェック
* 確認2. IFC開口階層構造について
* 確認3. 各パラメーター設定


## 開発について

本ソフトウェアは[hollyatsafe](https://community.safe.com/s/profile/0050c00000CztYeAAJ)が開発した[BIM to GIS (Intermediate) | IFC LOD 300 to LOD 4 CityGML](https://community.safe.com/s/article/bim-to-gis-intermediate-ifc-lod-300-to-lod-4-cityg)を参照し開発したものです。

## License
本ソフトウェアはApache-2.0 Licenceを適用します。

### 注意事項
•本レポジトリは参考資料として提供しているものです。動作保証は行っておりません。
•予告なく変更・削除する可能性があります。
•本レポジトリの利用により生じた損失及び損害等について、国土交通省及び著作権者はいかなる責任も負わないものとします。
