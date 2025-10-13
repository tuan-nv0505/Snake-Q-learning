# Q-learning for playing Snake game

## Introduction

Here is my Python source code for training an agent to play Snake using the Q-learning algorithm.

Talking about performance, my agent achieved a score of 70, which is much better than what I initially expected from a basic Q-learning approach.

It’s worth noting that Q-learning has an improved variant called Deep Q-Learning (DQN), which uses a Neural Network to approximate the Q-function and typically achieves much better results.

In this project, I focused only on the basic Q-learning algorithm. You can check out my Snake game with DQL implementation on my GitHub ([Snake Deep Q-learning](https://github.com/tuan-nv0505/Snake-double-deep-Q-learning)) to see the performance difference.

[//]: # (<p align="left">)

[//]: # (  <img src="demo/video-1-1.gif" width="200">)

[//]: # (  <img src="demo/video-1-2.gif" width="200">)

[//]: # (  <img src="demo/video-1-3.gif" width="200">)

[//]: # (  <img src="demo/video-1-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-2-1.gif" width="200">)

[//]: # (  <img src="demo/video-2-2.gif" width="200">)

[//]: # (  <img src="demo/video-2-3.gif" width="200">)

[//]: # (  <img src="demo/video-2-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-3-1.gif" width="200">)

[//]: # (  <img src="demo/video-3-2.gif" width="200">)

[//]: # (  <img src="demo/video-3-3.gif" width="200">)

[//]: # (  <img src="demo/video-3-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-4-1.gif" width="200">)

[//]: # (  <img src="demo/video-4-2.gif" width="200">)

[//]: # (  <img src="demo/video-4-3.gif" width="200">)

[//]: # (  <img src="demo/video-4-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-5-1.gif" width="200">)

[//]: # (  <img src="demo/video-5-2.gif" width="200">)

[//]: # (  <img src="demo/video-5-3.gif" width="200">)

[//]: # (  <img src="demo/video-5-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-6-1.gif" width="200">)

[//]: # (  <img src="demo/video-6-2.gif" width="200">)

[//]: # (  <img src="demo/video-6-3.gif" width="200">)

[//]: # (  <img src="demo/video-6-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-7-1.gif" width="200">)

[//]: # (  <img src="demo/video-7-2.gif" width="200">)

[//]: # (  <img src="demo/video-7-3.gif" width="200">)

[//]: # (  <img src="demo/video-7-4.gif" width="200"><br/>)

[//]: # (  <img src="demo/video-8-1.gif" width="200">)

[//]: # (  <img src="demo/video-8-2.gif" width="200">)

[//]: # (  <img src="demo/video-8-3.gif" width="200"><br/>)

[//]: # (  <i>Sample results</i>)

[//]: # (</p>)

## How to use my code

With my code, you can:

* **Train your model** by running `python train.py`.
* **Test your trained model** by running `python evaluate.py`.

## Requirements
* **numpy**
* **pygame**
