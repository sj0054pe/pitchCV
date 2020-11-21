中本真誉
====

## Project Title
野球における投球/打球フォームの定量解析アプリ

## ソフトについて
特定の投手について「直近の投球」と「過去の投球」のフォームを定量的に比較する。

## 機能
姿勢推定はHRNetを利用しました。  

## HRNetについて
書籍情報 : https://arxiv.org/abs/1902.09212 
github : https://github.com/leoxiaobin/deep-high-resolution-net.pytorch
lisence : https://github.com/leoxiaobin/deep-high-resolution-net.pytorch/blob/master/LICENSE

## 各プログラムの概要
複数のプログラムから構成されています。  
各プログラムの概要は以下の通りです。  

<1. HRNet_PoseEstimation.ipynb>
HRNetを利用した姿勢推定プログラム。

<2. HRNet_AniFigure1.ipynb>
HRNet_PoseEstimation.ipynbから生成した関節点の座標データをグラフ化するプログラム。
グラフには単一動作(ex)1回の投球)における関節位置の座標変化をプロットする。
<3. HRNet_AniFigure2.ipynb>
HRNet_PoseEstimation.ipynbから生成した関節点の座標データをグラフ化するプログラム。
グラフには複数動作(ex)ある投球と別の投球)における関節位置の座標変化をプロットする。また、関節ごと (右肩 / 右肘 / 右手首 / 左肩 / 左肘 / 左手首) でグラフを生成する。

## 必要条件
利用確認済みデバイス：Google colablatory ver. XXX

## 使い方


## 必要なパッケージのインストール
* pitchCVのインストール 所要時間：X分
  * 依存ファイル(OpenCVのビルドと実行に必要な機能を持つパッケージ)のインストール
