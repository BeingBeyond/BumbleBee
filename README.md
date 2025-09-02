# From Experts to a Generalist: Toward General Whole-Body Control for Humanoid Robots
<div align="center">

[[Website]](https://beingbeyond.github.io/BumbleBee/)
[[arXiv]](https://arxiv.org/abs/2506.12779)

[![Python Version](https://img.shields.io/badge/Python-3.10-blue.svg)]()
[![GitHub license](https://img.shields.io/badge/MIT-blue)]()

![](docs/images/framework.png)

</div>

We present BumbleBee (BB), an expert-generalist learning framework designed to achieve general agile whole-body control on humanoid robots. BB addresses the challenges of diverse motion demands and data conflicts by combining motion clustering and sim-to-real adaptation. Using an autoencoder-based clustering method, BB groups behaviorally similar motions and trains expert policies within each cluster. These experts are further refined with real-world data through iterative delta action modeling to bridge the sim-to-real gap. Finally, the expert policies are distilled into a unified generalist controller that maintains agility and robustness across all motion types. Extensive experiments on simulators and a real humanoid robot demonstrate that BB sets a new benchmark for agile, robust, and generalizable humanoid control. Real-robot videos are available on our [[Website]](https://beingbeyond.github.io/BumbleBee).


## Code
We will release our code soon.

## Citation
If you find our work useful, please consider citing us!
```
@article{wang2025experts,
  title={From Experts to a Generalist: Toward General Whole-Body Control for Humanoid Robots},
  author={Yuxuan Wang and Ming Yang and Ziluo Ding and Yu Zhang and Weishuai Zeng and Xinrun Xu and Haobin Jiang and Zongqing Lu},
  journal={arXiv preprint arXiv:2506.12779},
  year={2025}
}
```
