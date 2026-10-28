# MX TRAIL — Android 開発試遊版

TF250-Eで4つのオフロードコースを走る、REX WORKSの個人制作ゲームです。

**現在の配布版: 0.2.0-trial.96（2026-10-28）。画質確認用の開発版・最適化前です。**

OFVのスタート〜第1ヘアピン（約100m）の景観・路面・ライダーと車体の材質を重点的に更新しました。全コースの美術が完成した版ではありません。

**描画負荷が高く、確認端末で約16fpsです。** Lenovo Legion Tab 8.8 Gen 3の録画なし・第1ヘアピン約11.86秒の短時間計測は平均16.19fpsでした。30fps・60fpsには達しておらず、長時間の性能や他機種の動作は保証できません。滑らかさの改善は今後の工程です。

## ダウンロード

- [REX WORKSの紹介・インストール案内](https://rex-works-site.rex-kitaura.workers.dev/games/mx-trail/)
- [Android APKをダウンロード（約227MB）](https://github.com/rexkitaura/mx-trail-releases/releases/download/v0.2.0-trial.96/MXTrail-0.2.0-trial.96.apk)
- [リリース情報と確認用ファイル](https://github.com/rexkitaura/mx-trail-releases/releases/tag/v0.2.0-trial.96)

GitHubアカウントや支払いは不要です。通信料は利用する回線の契約によります。

## 対応環境・遊べる内容

Android 8.0以上・64bit ARM（arm64-v8a）。実機確認はLenovo Legion Tab 8.8 Gen 3です。その他の端末は未確認です。iPhone・iPad、32bit Android、PCにはこのAPKをインストールできません。

- SUGO / OFV / KODAMA / KEGONの4コース、レースとフリー走行。
- 初めに触れた位置を起点にする左右のアナログ操作。左は操舵・前後荷重、右は上へアクセル・下へブレーキ。
- 実車のギア比を基にした6段オート変速、回転数に同期するエンジン音。
- 旋回と出口加速の荷重操作、ON/OFFできる走行ガイドと推奨ライン。
- 転倒地点での起き上がり、詰まり時のコース復帰と低速スピンターン。

詳しい操作と導入方法は [INSTALL_JA.md](INSTALL_JA.md) を参照してください。操作感やライダーの動作も調整中です。

## 更新・旧版

同じ署名のUnity版はアンインストールせず上書きで更新できます。旧Web版の公開プレイと旧WebView APK 0.1.1の配布は終了し、Android版の案内に統一しました。旧WebView版とは別アプリで、旧版セーブの移行には対応していません。

このリポジトリはAPKと配布資料の公開用です。ゲームのソースコードは含みません。第三者素材の出典・ライセンスは [licenses](licenses/) に収録しています。コース名・車両名等の記載は各権利者による監修・提携を意味しません。
