# Final competition

## Rules

1. Stageシミュレータのフィールドに最低３か所の座標（以降、Check point と表記）を設定し、ロボットがそれらを順番に最後まで移動する。
   1. Check point の場所は任意だが navigation によって確実に到達可能なルートを設定すること。
   2. あまりに短距離の移動しかしていない場合は、ランキング決定時の評価（後述）で減点となる可能性がある。
2. 各チェックポイントでは Windows Side の画像処理を活用したミニゲームを起動すること。ミニゲームにはROS Sideのロボットの動作を含めても構わない。

## Submissions

完成したソフトウェアに基づき、以下のものを9/3（金）のタイ時間12:00、日本時間14:00までに成果物として提出する。提出フォームは後日SLACKで公開される。

1. 各ミニゲームの説明スライド。
   1. Team Developmentsで実施した要領で作成すること。iPBL最終日のプレゼンテーション（７分）で使用される（後述）。
2. ミニゲームのプレイ動画。
   1. 全てのミニゲームのプレイの様子を１０分以内の一つの動画ファイルにまとめる。
   2. この動画はYouTubeに限定公開でアップロードされ、iPBL最終日に参加者・関係者に視聴される（後述）。
3. ROS パッケージのソースコード (`~/catkin_ws/src`以下のディレクトリ群)。
   1. [How to access files and directories in the ROS container](https://github.com/oit-ipbl/portal/blob/main/setup/dockerros.md#how-to-access-files-and-directories-in-the-ros-container) の方法により Windows から ROS Container 内のディレクトリにアクセスし、`zip`圧縮したものを提出する。
   2. Windows OS からは`\\wsl$\docker-desktop-data\version-pack-data\community\docker\volumes\melodicvnc4_catkin_ws\_data\src`にアクセスするとディレクトリを閲覧できる。
   3. 下図の通り`CMakeList.txt`以外のディレクトリを`zip`圧縮し、ファイル名を`teamXX.zip`（`XX`には`a, b, c...`といったチーム名が入る）として提出すること。  
   ![2021-08-18_083817.svg.png](./images/2021-08-18_083817.svg.png)
4. Windows Sideの＊＊をZIP圧縮したもの。
5. セットアップマニュアル、ゲームの操作マニュアル。
   1. PDFファイルで提出する。作成ツールは任意である。

## Evaluation criteria

各チームが作成したプレゼンテーション、およびデモ実演、プレイ動画、相互鑑賞会での説明に基づき以下の観点から１０点満点で採点する。  
<!-- 作品の一部分でも良い箇所があれば、積極的に評価すること。 -->

1. Technical aspects 0～5点：技術的に優れているかどうか。
2. Attractive aspects 0～5点：ゲームとしての面白さ、魅力に優れているか。
