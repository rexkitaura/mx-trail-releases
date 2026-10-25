# MX TRAIL Android 試遊版 0.2.0-qa.67

現在制作中のAndroid版を、無料で試遊できるAPKとして公開します。**正式版ではありません。**

[REX WORKSの紹介・インストール案内](https://rex-works-site.rex-kitaura.workers.dev/games/mx-trail/)

## 収録内容

- SUGO / OFV / KODAMA / KEGONの4コース。レースとフリー走行。
- TF250-Eの操舵・加減速・前後荷重、6段オート変速。
- 回転数に同期するエンジン音と回転計、転倒地点で起き上がる機能。
- RACE STRIP UI、短く内側に配置したアナログのアクセル／ブレーキ。

## 導入

Assetsの **MXTrail-0.2.0-qa.67.apk** をAndroid端末でダウンロードしてください。`Source code (zip)` / `Source code (tar.gz)` は配布資料で、ゲーム本体ではありません。

Android 8.0以上・64bit ARM向け。APKは約157MB（157,411,364 bytes）。実機確認端末はLenovo Legion Tab 8.8 Gen 3です。その他の端末は未確認です。

詳しい手順は添付の `INSTALL_JA.md` に記載しています。Playプロテクトなどがインストールをブロックする場合、保護機能を無効にせず中止してください。

## 調整中の点

森林コースなど高負荷の場面ではフレームレートが下がります。持続60fps、グラフィックス全体、ライダーの動作、タッチ操作の最終調整は完了していません。

旧Web版・WebView APK 0.1.1は引き続き利用できます。このUnity版とは別アプリで、旧版のセーブデータは引き継ぎません。

## 検証情報

APKは非デバッグ構成で署名済み。versionCodeは267です。確認用のSHA-256と署名証明書のフィンガープリントを `release-manifest.json` に、素材のライセンスを `THIRD_PARTY_NOTICES.txt` に収録しています。

```text
f3da9407a248763888755003205aa84b72605bff38718fcbd25e46d8a56aedab  MXTrail-0.2.0-qa.67.apk
```
