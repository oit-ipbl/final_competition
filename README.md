# Final competition

## Rules

1. Set three or more coordinates (hereinafter called `Check point`) on Stage simulator field. Your robot should move all of the `check points` one by one.
   1. The `check points`' locations are arbitrary, but your robot must pass through them by [`ROS navigation`](https://github.com/oit-ipbl/robots/blob/main/robot_control/robot_control_03.md#ros-navigation). Cafully check and test your programs to ensure that the robot can reach the `check points`.
   2. If distances between `check points` are so short, [evaluation score](#evaluation-criteria) of your programs may be low.
2. A mini-game including Windows side [`image processing techniques`](https://github.com/oit-ipbl/image_processing) should be launched, when the robot reach each `check point`. Therefore, you should implement three mini-games at minimum.

## Submissions

You should submit the following materials until 9/3 12:00 (Thai), 14:00 (Jp).  
The submission form will be annouced at SLACK.

1. Slide for presentation of your mini-games.
   1. Make 7 minitues presentation slide, like as [Exercise1 (team development)](https://github.com/oit-ipbl/Integration/blob/main/team_exercise/team_exercise.md#exercise1-team-development).
   2. File format and edit tools are not limited.
2. Play movie of the games.
   1. Muximum time of the movie is 10 minitues, and should include all of your mini-games' demo play.
   2. The movie will be uploaded with `unlisted` style, and all iPBL participants will see it for evalucation of your final-competition work.
   3. File format is popular movie format, such as `mp4`, `wmv` and so on.
3. ROS packages' source code, that is directories under `~/catkin_ws/src`.
   1. Check [How to access files and directories in the ROS container](https://github.com/oit-ipbl/portal/blob/main/setup/dockerros.md#how-to-access-files-and-directories-in-the-ros-container) again, and access the directories of the ROS container from Windows.
   2. Open `\\wsl$\docker-desktop-data\version-pack-data\community\docker\volumes\melodicvnc4_catkin_ws\_data\src` from Windows file manager.
   3. Make a `zip` archive of the directries. The `CMakeList.txt` is **NOT** needed. The `zip` filename is `teamXX.zip`. `XX` means you team name (`a, b, c...`).  
   ![2021-08-18_083817.svg.png](./images/2021-08-18_083817.svg.png)
4. Windows Sideの＊＊をZIP圧縮したもの。
5. Operation manual of your softweare. The manual may include launch sequencs of your ROS packages and Windows side programs, play manual of your mini-games, etc.
   1. File format is PDF. Edit tools are not limited.

## Evaluation criteria

Your work will be scored 0 to 10 points, based on the presentation, movie and demo session at the final day of this iPBL.  
作品の一部分でも良い箇所があれば、積極的に評価すること。
The score is composed of the following two aspects.

1. Technical aspects (0 to 5 points): Superiority of image processing or robotics techniques.
2. Attractive aspects (0 to 5 points): ゲームとしての面白さ、魅力に優れているか。

## Presentation, demo session, scoring and ranking

Final competition will be held at 9/4, the final iPBL day, from 11:00 (Thai), 13:00 (Jp). Location is oVice.  
The competition is composed of the following parts.

1. 11:00 - 13:00 Final competition Part A, team presentation.
   1. 7 minitues presentation with your slide.
   2. Presentation order is rondom, and announed at 9/3 17:00 (Thai), 19:00 (Jp) on SLACK.
2. 14:00 - 16:00 Final competition Part B, demo session.
   1. All teams present demo play and movie of mini-games on their demo space, which will be built on oVice. Team members should wait at the demo space for iPBL participants and audiences, and show the demo, give explanations of the games and answer the questions from the participants and audiences.  
   Demo session is divided into the following sub-parts.
   2. 14:00 - 15:00 OIT Students can see other teams' demo freely and should evaluate. SIIT Students should wait at their team's space and presents the demo.
   3. 15:00 - 16:00 SIIT Students can see other teams' demo freely and should evaluate. OIT Students should wait at their team's space and presents the demo.
3. Scoring and ranking
   1. [As previously mentioned](#evaluation-criteria), all iPBL participants evaluate the each team's final-compmetition work with 0 to 10 points, and submit the score via MS Forms.
   2. 参加者は自チームの採点は行わない。
4. Ranking is determined with average score, and award will be given.

Note that, the time schedules may be changed according to the situations.
