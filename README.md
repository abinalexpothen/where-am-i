# where-am-i

This is the third project in a series of projects within the Udacity Robotics Software Engineer Nanodegree program. In this project, adaptive montecarlo localization (amcl) is used to localize a skid-steer robot with laser scanner in a known map of the world. 

Particle distribution at **initialization** of the world and the amcl package:
![rviz_screenshot_2021_09_15-23_46_02](https://user-images.githubusercontent.com/23329551/133546679-843b4c1b-3077-4cc7-993a-9ec76a84f8ad.png)

Particle distribution **after performing tele-operation**:
![rviz_screenshot_2021_09_15-23_44_21](https://user-images.githubusercontent.com/23329551/133546992-5f9c1ddc-7133-4941-bb5c-f43d6dc097a7.png)

Note that the red arrows, represeting the particles, converge and the corresponding pose is shown as a green arrow. The laser scan show that the known map is aligned with the walls
