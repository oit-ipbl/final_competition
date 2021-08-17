# Final competition

## Rules

1. Stageシミュレータのフィールドに最低３か所の座標（以降、Check point と表記）を設定し、ロボットがそれらを順番に最後まで移動する。
   1. Check point の場所は任意だが navigation によって確実に到達可能なルートを設定すること。
   2. あまりに短距離の移動しかしていない場合は、ランキング決定時の評価（後述）で減点となる可能性がある。
2. 各チェックポイントでは Windows Side の画像処理を活用したミニゲームを起動すること。ミニゲームにはROS Sideのロボットの動作を含めても構わない。

## Submissions

完成したソフトウェアに基づき、以下のものを9/3（金）のタイ時間12:00、日本時間14:00までに成果物として提出する。提出フォームは後日SLACKで公開される。

1. 各ミニゲームの説明スライド。
   1. Team Developmentsで実施した要領で作成すること。iPBL最終日のプレゼンテーション（５分）で使用される（後述）。
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
作品の一部分でも良い箇所があれば、積極的に評価すること。

1. Technical aspects 1～5点：技術的に優れているかどうか。
2. Attractive aspects 1～5点：ゲームとしての面白さ、魅力に優れているか。

## Presentation, scoring and ranking

iPBL最終日、9/4（土）のタイ時間＊＊時よりoViceで成果発表会を実施し、チームの順位付けを行う。なお、以下の全ての時刻設定は当日の進行によって変更する可能性がある。

1. 11:00 - 13:00 Final competition Part A, team presentation.
   1. 各チームがスライドを使って発表する。発表時間は７分、交代時間は１分である。
   2. 発表順はランダムに決定し9/3（金）のタイ時間17:00、日本時間19:00にSLACKのgeneralチャンネルで公開される。
2. 14:00 - 16:00 Final competition Part B, demo movie, scoring and ranking.
   1. プレゼンテーション後、oVice上に施設されたチームごとのスペースにおいてミニゲームのデモと動画を公開しチーム相互で鑑賞しあう。この鑑賞は以下の時間割で行う。鑑賞中の質疑は英語で行わなければならない。
   2. 14:00 - 15:00 OIT Studentsは自由に鑑賞し、SIIT Studentsはチームのスペースで説明を担当する。
   3. 15:00 - 16:00 SIIT Studentsは自由に鑑賞し、OIT Studentsはチームのスペースで説明を担当する。
3. チーム相互の採点と教員採点によりランキングを決める。iPBL参加者と教員は前述した評価基準に基づき採点した合計得点をFormから投稿する。
   1. 参加者は自チームの採点は行わない。
4. Formから投稿された点数の平均点をもってランキングを発表し、表彰を行う。
