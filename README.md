# LineageOS Hosting repository
このリポジトリでは、[LineageOS 14.1](https://github.com/coara-chocomaru/test)を使ってビルドされた、Lineage Updaterを使用可能にするための設定ファイルとバイナリOTAファイルを提供します。

## ファイル
- `updates_gapps.json` :
GAppsを含むバージョン用。
- `updates_ngapps.json` :
GAppsを含まないバージョン用。
- `get_build_date.sh` :
ビルド環境でbuild.propからUnixタイムスタンプを取得するスクリプト。
- `lineage_recovery.img` :
LineageOS Recoveryは最適化されておらずトラブルの原因になるため削除しました。

## warning
ここでリリースされているOTAファイルを販売されていることが発覚した場合は、このリポジトリを含め関連するリポジトリも全て非公開または削除にします。その場合、システムアップデートはそれ以上提供されなくなりますのでご注意ください。
