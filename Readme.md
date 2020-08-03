# Soft Tissue Robotics Tutorials

Within the [DFG graduate school Soft Tissue Robotics](https://www.str.uni-stuttgart.de/) PhD students of the University of Stuttgart, Germany, and the University of Auckland, New Zealand, investigate new simulation-driven methods for manipulating deformable objects with robotic devices. 


As part of the teaching curriculum, intedisciplinary tutorial sessions were held between the PhD students. This repository aims to collect the tutorial sessions that are based on shareable code.

### Acknowledgment

The research leading to this publication has received funding from the German Research Foundation (DFG) as part of the International Research Training Group “Soft Tissue Robotics” (GRK 2198/1). 

## How-to

Clone the repository via 

```sh
# fresh clone
git clone --recursive git@github.com:chhinze/SoftTissueRobotics.git

# later update:
git pull
git submodule update --remote --merge
```

This will synchronize all the tutorial sessions. Note, that the individual tutorials may have dependencies, which need to be installed in order to get them running. These dependencies can be found in the readme files of each tutorial, which are linked below. 

## Contents

| Directory                          | Description | Language |
| ---------------------------------- | ----------- |----------|
| [`tutorials/openmp-exercise`](https://github.com/maierbn/openmp-exercise/blob/master/README.md) | Introduction and exercises in OpenMP | C++ |
| [`tutorials/panda_tutorial`](https://github.com/chhinze/panda_tutorial/blob/master/Readme.md) | Introduction in Eigen3 Math and C++-API of Franka Emika Panda robot | C++ |
| [`tutorials/tutorial_on_DART`](https://github.com/markuswnuk91/tutorial_on_DART/blob/master/README.md)       | Tutorial on Multibody Physics Simulation with [DART](http://dartsim.github.io/) | C++ |
| [`tutorials/vumat-linelast-example`](https://github.com/harnoorsaini/vumat-linelast-example/blob/master/readme.md) | Introduction in writing a VUMAT with ABAQUS | ABAQUS |