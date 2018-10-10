# rctf-list

The Robotics Capture the Flag (RCTF) is an online playground to challenge robot security from your browser. It is designed to be an online game, available 24/7, launchable through your browser and designed to learn robot hacking step by step.

This repository contains a list of the scenarios available in the [Robotics CTF](http://rctf.aliasrobotics.com).

| Scenario | Short description | Author/s | Status |
|-----|-----|------|------|
| [rctf-scenario1](https://github.com/aliasrobotics/rctf-scenario1) | Unprotected topics show a lot of interesting information. Search on them to get your answer. Useful tools: rostopic  | [aliasrobotics](https://github.com/aliasrobotics)  | Active |
| [rctf-scenario2](https://github.com/aliasrobotics/rctf-scenario2) | In ROS2, even if security measures are available, not configuring them leverages to the same results as in ROS1. Useful tools: ros2 topic | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario3](https://github.com/aliasrobotics/rctf-scenario3) |  The dinosaurs are out of control, and the node that controls the gates is not letting us in. Try to guess what the node wants so you can access the next scenario. | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| [rctf-scenario4](https://github.com/aliasrobotics/rctf-scenario4) | Even if collaborative robots are fun to play with, if they are out of control, they can be dangerous too! Try to hit our friend, Pruden, with the robot in order to get the flag. | [aliasrobotics](https://github.com/aliasrobotics) | Active |
| .... |... |... |...|

## Create your own scenario
We invite security researchers to create their own robotics security scenarios and share them with the community. We accept such contributions through [Pull Request](https://github.com/aliasrobotics/rctf-list/pulls). To create your own scenario, start from [this simple template](https://github.com/aliasrobotics/rctf-scenario1).

## Cite our work
```
@ARTICLE{2018arXiv181002690O,
            author = {{Olalde Mendia}, G. and {Usategui San Juan}, L. and {Perez Bascaran}, X. and 
           {Bilbao Calvo}, A. and {Hern{\'a}ndez Cordero}, A. and {Zamalloa Ugarte}, I. and 
           {Mu{\~n}iz Rosas}, A. and {Mayoral Vilches}, D. and {Ayucar Carbajo}, U. and 
           {Alzola Kirschgens}, L. and {Mayoral Vilches}, V. and {Gil-Uriarte}, E.
           },
             title = "{Robotics CTF (RCTF), a playground for robot hacking}",
           journal = {ArXiv e-prints},
         archivePrefix = "arXiv",
            eprint = {1810.02690},
          primaryClass = "cs.CY",
          keywords = {Computer Science - Computers and Society, Computer Science - Robotics},
              year = 2018,
             month = oct,
            adsurl = {http://adsabs.harvard.edu/abs/2018arXiv181002690O},
           adsnote = {Provided by the SAO/NASA Astrophysics Data System}
         }
```
