# frontiers2021_gazebo_worlds

The `frontiers2021_gazebo_worlds` ROS package provides a collection of Gazebo worlds and models for frontiers2021 .

**Content:**

*   [Getting Started](#getting-started)
*   [Submodule Integration](#submodule-integration)
*   [Contribution Guidelines](#contribution-guidelines)

## Getting Started

Add the Gazebo models of the `frontiers2021_gazebo_worlds` ROS package to the `GAZEBO_MODEL_PATH` of your shell environment.

```shell
export GAZEBO_MODEL_PATH=${GAZEBO_MODEL_PATH}:/path/to/frontiers2021_gazebo_worlds/models/
```

## Submodule Integration

Assuming that SSH access has been granted:

```shell
git submodule add -b devel --name frontiers2021_gazebo_worlds git@gitlab.com:naripa/frontiers2021_gazebo_worlds.git catkin_ws/src/frontiers2021_gazebo_worlds
```

Make sure that the `devel` branch is tracked.

## Contribution Guidelines

This repository strictly enforces file name conventions. Please use prefixes to distinguish 1st-party resources from 3rd-party ones. Also, all file names should follow the ROS conventions: use small characters and underscores `_` exclusively.

> For example, add the prefix `nrp_` to the file names of NAIST-RITS-Panasonic worlds and models. Other prefixes currently in use are `hsr_` (Toyota HSR Community), `tnp_` (Team NAIST-Panasonic), `wrs_` (World Robot Summit), and `3rd_` (3rd-party resources).
