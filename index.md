---
layout: main
title: robosuite
subtitle: 
project_tagline: "A Modular Simulation Framework and Benchmark for Robot Learning"
description: "robosuite: A Modular Simulation Framework and Benchmark for Robot Learning"
videoId: "robosuite-video-faster.mp4"
---

![pull figure]({{ 'assets/images/gallery_logo.jpg' | absolute_url }})

**robosuite** is a simulation framework powered by the [MuJoCo](http://mujoco.org/) physics engine for robot learning. It also offers a suite of benchmark environments for reproducible research. The current release (v1.3) features rendering tools, ground-truth of vision modalities, and camera utilities. This project is part of the broader [Advancing Robot Intelligence through Simulated Environments (ARISE) Initiative](https://github.com/ARISE-Initiative), with the aim of lowering the barriers of entry for cutting-edge research at the intersection of AI and Robotics.

# New Releases
- [10/19/2021] **v1.3**: Ray tracing and physically based rendering tools :sparkles: and access to additional vision modalities [video spotlight](https://www.youtube.com/watch?v=2xesly6JrQ8) [release notes](https://github.com/ARISE-Initiative/robosuite/releases/tag/v1.3)

- [02/17/2021] **v1.2**: Added observable sensor models :eyes: and dynamics randomization [release notes](https://github.com/ARISE-Initiative/robosuite/releases/tag/v1.2)

- [12/17/2020] **v1.1**: Refactored infrastructure and standardized model classes for much easier environment prototyping [release notes](https://github.com/ARISE-Initiative/robosuite/releases/tag/v1.1)

# Video Overview

{% include video/rawVideo.html fileName=page.videoId %}

# Team

{% include members.html %}

# Citation

```bibtex
@inproceedings{robosuite2020,
  title={robosuite: A Modular Simulation Framework and Benchmark for Robot Learning},
  author={Yuke Zhu and Josiah Wong and Ajay Mandlekar and Roberto Mart\'{i}n-Mart\'{i}n},
  booktitle={arXiv preprint arXiv:2009.12293},
  year={2020}
}
```
