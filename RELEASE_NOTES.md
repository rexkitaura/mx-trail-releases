# MX TRAIL 0.2.0-trial.96 — 画質確認用の開発版

**最適化前の高負荷版です。** OFVのスタート〜第1ヘアピン（約100m）の画質を重点更新しました。全体の完成版ではありません。

Lenovo Legion Tab 8.8 Gen 3で録画なし約11.86秒の旋回を計測し、平均 **16.19fps** でした。30fps・60fpsは未達で、長時間の性能・他端末の動作は未確認です。

[REX WORKSの紹介・導入案内](https://rex-works-site.rex-kitaura.workers.dev/games/mx-trail/)

## qa.67からの主な更新

- OFV第1ヘアピンの土・わだち、路肩、横断幕・テント・計時台・サービス棟、遠景、ライダーとバイクの材質・陰影。
- 最初に触れた位置を起点にする左右のアナログパッド。右は上へアクセル・下へブレーキ、終端を越えても100%を維持。
- ギア比に基づく変速・RPM、わだち旋回と出口加速の補助、ON/OFFできる走行ガイド。
- 詰まり時の近傍コース復帰と低速スピンターン。

4コースとレース／フリー走行を収録していますが、今回の美術の重点区間はOFVです。操作感、人物の動作、全コースの美術と60fps化は引き続き調整します。

## ダウンロード・更新

Assetsの **MXTrail-0.2.0-trial.96.apk** を選んでください。約227MB（226,743,584 bytes）、Android 8.0以上・64bit ARM向けです。`Source code (zip)` / `Source code (tar.gz)` は配布資料で、ゲーム本体ではありません。

同じ署名のUnity版は上書きで更新できます。詳しくは添付の `INSTALL_JA.md` をご覧ください。旧Web版の公開プレイ・旧WebView APK配布は終了し、Android版の案内へ統一しました。旧版セーブの移行には対応していません。

## 検証情報

通常署名の非デバッグAPK、versionCode 296。Android1にUSB導入して確認したものと同じファイルです。素材のライセンスは `THIRD_PARTY_NOTICES.txt`、詳細は `release-manifest.json` に収録しています。

```text
92c049b2e52375fcb154c4679d4f6a972c22e4476f54e5663b678c5b5d21c3d8  MXTrail-0.2.0-trial.96.apk
```
