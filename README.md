# FlatShadowCaster

## 概要

FlatShadowCaster は、カメラベースでリアルタイムにスプライトの平面的な影を生成する Unity コンポーネントです。
スーパーマリオメーカーで見られるような影エフェクトを簡単に実現できます。

## 使い方

1. リポジトリを clone、もしくは release から FlatShadowCaster.unitypackage をダウンロード
2. ダウンロードしたファイルを Unity で開く
3. GameObject に `FlatShadowCaster`コンポーネントを追加
4. 以下の設定を調整：

   - **Color**: 影の色
   - **Distance**: 影のオフセット距離
   - **Shadow Resolution**: 描画解像度の倍率
   - **Target Layer**: 影を生成する対象レイヤー
   - **Shadow Sorting Layer Name**: 影のソーティングレイヤー

## 動作確認環境

- Unity 6000.0.23f1
- URP

## サンプル

`Assets/FlatShadowCaster/Sample/`にサンプルシーンが含まれています。
