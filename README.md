# Obstacle Tower Environment

![alt text](banner.png "Obstacle Tower")

## About

The Obstacle Tower is a procedurally generated environment consisting of multiple floors to be solved by a learning agent. It is designed to test learning agents abilities in computer vision, locomotion skills, high-level planning, and generalization. It combines platforming-style gameplay with puzzles and planning problems, and critically, increases in difficult as the agent progresses.

Within each floor, the goal of the agent is to arrive at the set of stairs leading to the next level of the tower. These floors are composed of multiple rooms, each which can contain their own unique challenges. Furthermore, each floor contains a number of procedurally generated elements, such as visual appearance, puzzle configuration, and floor layout. This ensures that in order for an agent to be successful at the Obstacle Tower task, they must be able to generalize to new and unseen combinations of conditions.

### Reference Paper

To learn more, read our AAAI Workshop paper on the Obstacle Tower [here]().

It can be cited as:

[to be added]

### Version History

* v1.0 - Initial Release.

## Installation

### Requirements

The Obstacle Tower environment runs on Mac OS X, Windows, or Linux.

Python dependencies (also in [setup.py](https://github.com/Unity-Technologies/obstacle-tower-env/blob/master/setup.py)):
* Unity ML-Agents v0.6
* OpenAI Gym
* Pillow

### Download the environment

| *Platform*     | *Download Link*                                                                     |
| --- | --- |
| Linux (x86_64) | https://storage.googleapis.com/obstacle-tower-build/v1/obstacletower_v1_linux.zip   |
| Mac OS X       | https://storage.googleapis.com/obstacle-tower-build/v1/obstacletower_v1_osx.zip     |
| Windows        | https://storage.googleapis.com/obstacle-tower-build/v1/obstacletower_v1_windows.zip |

### Install the Gym interface

```bash
$ git clone git@github.com:Unity-Technologies/obstacle-tower-env.git
$ cd obstacle-tower-env
$ pip install -e .
```

## Getting Started

To see an example of how to interact with the environment, see our [basic usage Jupyter notebook](examples/basic_usage.ipynb).