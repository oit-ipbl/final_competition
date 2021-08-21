# Final competition

## Rules

1. Set 3 or more coordinates (hereinafter called `Check point`) on the Stage simulation field. Your robot should move all of the `check points` one by one.
   - The `check points`' locations are arbitrary, but your robot must pass through them by [`ROS navigation`](https://github.com/oit-ipbl/robots/blob/main/robot_control/robot_control_03.md#ros-navigation). Carefully check and test your programs to ensure that the robot can reach the `check points`.
   - If distances between `check points` are so short, [evaluation score](#evaluation-criteria) of your programs may be low.
2. A mini-game including Windows side [`image processing techniques`](https://github.com/oit-ipbl/image_processing) should be launched, when the robot reaches each `check point`. Therefore, you should implement 3 mini-games at a minimum.

## Submissions

Each team should submit the following 5 materials by 9/3 12:00 (Thai), 14:00 (Jp).  
The submission form will be announced on SLACK.

1. Slide for the presentation of your team's mini-games.
   - Make 7 minutes presentation slide, like [Exercise1 (team development)](https://github.com/oit-ipbl/Integration/blob/main/team_exercise/team_exercise.md#exercise1-team-development).
   - File format and edit tools are not specified.
2. A video of gameplay.
   - The maximum time of the video is 10 minutes, and should include all of the mini-games' demo play.
   - The video will be uploaded to YouTube with `unlisted` style, and all iPBL participants will see it for evaluation of your team's final-competition works.
   - File format should be popular video format, such as `mp4`, `wmv` and so on.
3. ROS packages' source code, that is zipped the files in directories under `~/catkin_ws/src`.
   - Check [How to access files and directories in the ROS container](https://github.com/oit-ipbl/portal/blob/main/setup/dockerros.md#how-to-access-files-and-directories-in-the-ros-container) again, and access the directories of the ROS container from Windows.
   - Open `\\wsl$\docker-desktop-data\version-pack-data\community\docker\volumes\melodicvnc4_catkin_ws\_data\src` from Windows file manager.
   - Make a `zip` archive of the directories. The `CMakeList.txt` is **NOT** needed. The `zip` filename is `teamXX.zip`. `XX` means your team name (`a, b, c...`).  
   ![2021-08-18_083817.svg.png](./images/2021-08-18_083817.svg.png)
4. Zipped files of all source codes and images for Windows Side each content.
5. Operation manual of your software. The manual may include the start-up procedure of your ROS packages and Windows side programs, play manual of the mini-games, etc.
   - The file format should be PDF. Editor tools are not specified.

## Evaluation criteria

The final-competition works will be scored 0 to 10 points, based on the presentation, video, and demo session on the final day of this iPBL.  
If there is a good part of the work, add points positively.  
The score is composed of the following 2 aspects.

1. Technical aspects (0 to 5 points): Superiority of image processing or robotics techniques.
2. Attractive aspects (0 to 5 points): Attraction of the content.
