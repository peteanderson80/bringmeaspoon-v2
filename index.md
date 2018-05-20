
<p><span style="color: #ee5f5b; font-weight: bold;">NEW!</span> Our Vision-and-Language Navigation <a href="https://evalai.cloudcv.org/web/challenges/challenge-page/97/overview">test server and leaderboard</a> is up on EvalAI.</p>

## Room-to-Room (R2R) Navigation

{% include demo.html %}

R2R is the first benchmark dataset for visually-grounded natural language navigation in real buildings. The dataset requires autonomous agents to follow human-generated navigation instructions in previously unseen buildings, as illustrated in the demo above. For training, each instruction is associated with a Matterport3D Simulator trajectory. 22k instructions are available, with an average length of 29 words. There is a **test evaluation server** for this dataset available at [EvalAI](https://evalai.cloudcv.org/web/challenges/challenge-page/97/overview). 

We are currently setting up a test evaluation server for this dataset.

## Matterport3D Simulator

The Matterport3D Simulator enables the development of AI agents that interact with real 3D environments using visual information (RGB-D images). It is primarily intended for research in deep reinforcement learning, at the intersection of computer vision, natural language processing and robotics. Visual imagery for the simulator comes from the [Matterport3D dataset](https://niessner.github.io/Matterport/), containing comprehensive panoramic imagery and other data from 90 large-scale buildings. The Matterport3D Simulator is available on [GitHub](https://github.com/peteanderson80/Matterport3DSimulator).

## CVPR Paper

This work has been selected for a **spotlight oral presentation** at [CVPR 2018](http://cvpr2018.thecvf.com/). Initial results were also presented at the [NIPS 2017 ViGIL workshop](https://nips2017vigil.github.io/). If you use the Matterport3D simulator or the R2R dataset, please cite our [paper](https://arxiv.org/pdf/1711.07280){:target="_blank"}:

[![Paper](assets/1711.07280v2.jpg)](https://arxiv.org/pdf/1711.07280){:target="_blank"}

```
@inproceedings{mattersim,
  title={Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments},
  author={Peter Anderson and Qi Wu and Damien Teney and Jake Bruce and Mark Johnson and Niko S{\"u}nderhauf and Ian Reid and Stephen Gould and Anton van den Hengel},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
}
``` 

We also ask that you acknowledge the underlying Matterport3D dataset by also citing their paper:

```
@article{Matterport3D,
  title={Matterport3D: Learning from {RGB-D} Data in Indoor Environments},
  author={Chang, Angel and Dai, Angela and Funkhouser, Thomas and Halber, Maciej and Niessner, Matthias and Savva, Manolis and Song, Shuran and Zeng, Andy and Zhang, Yinda},
  journal={International Conference on 3D Vision (3DV)},
  year={2017}
}
``` 

## People

{% include people.html %}

## Future Work

To drive research in new and more challenging directions, we plan to release several related datasets at the intersection of computer vision, natural language processing and robotics.

{% include signup.html %}

## Acknowledgements

We would like to thank [Matterport](https://matterport.com/) for allowing the Matterport3D dataset to be used by the academic community. This project is supported by a [Facebook ParlAI Research Award](https://research.fb.com/announcing-the-winners-of-the-facebook-parlai-research-awards/), and by the [Australian Centre for Robotic Vision](https://www.roboticvision.org/).

{% include acrv-logo.html %}

