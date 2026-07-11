# Cornix Seoto ZMK Config

LiNEA40向けのせおと配列を、Cornix（50ポジション）向けに移植したZMK設定です。

## 配置方針

- 左手の左端列と右手の右端列は、全レイヤーで `&none` にしています。
- トラックボール、ポインティング、オートマウス、スクロールセンサー関連の設定は含めていません。
- せおと日本語、英字、記号、数字、Function、Wirelessの各レイヤーを維持しています。
- Cornixの親指6キーには、Function、記号Space、入力方式切替、Number Enter、記号Space、Wirelessを割り当てています。
- LiNEA40下段にあったコピー専用キーと上下矢印専用キーは、Cornixのキー数に合わせて省略しました。矢印は通常層上段とNumber層から入力できます。

## ビルド

GitHubへpushするとActionsが以下をビルドします。

- `cornix_left_seoto`
- `cornix_right_seoto`
- 左右のsettings resetファームウェア

Cornixのボード定義には [hitsmaxft/zmk-keyboard-cornix](https://github.com/hitsmaxft/zmk-keyboard-cornix) を使用しています。

## 元キーマップ

[Yoshiki613/zmk-config-LiNEA40-seoto](https://github.com/Yoshiki613/zmk-config-LiNEA40-seoto)
