# インターンシップ準備　手順書

## 利用するツール
- kaggle  
データサイエンスのコンペティションサイト。プライベートはコンペティションを開催可能なので、参加者にコンペティション上で精度を競ってもらう。
- Sony Nueral Network Console  
GUIでニューラルネットワークを構築可能なソフトウェア。データセットの分割、学習経過の観察、簡単な前処理、予測の実施なども簡単にGUI上から行うことができる。


## 各アカウントの準備
- kaggle(inClassで競うため)
- sony(Nueral Network Console利用のため)

## データセット
Food-101を利用。以下のリンクからダウンロード。サイズが大きいので気を付けること。  
[Food-101 download](https://www.vision.ee.ethz.ch/datasets_extra/food-101/)


解凍し、以下のスクリプトを実行する。  
setup.py input_dir output_dir  
利用するクラスの抽出、画像のリサイズを行う。  
処理をしたデータセットを再度zipファイルにして、当日利用するインターンフォルダへ格納する。

