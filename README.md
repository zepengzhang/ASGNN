# ASGNN
<div align="center">

<h1>Graph Neural Networks with Adaptive Structures</h1>

<div>
    <a href='https://zepengzhang.com/' target='_blank'>Zepeng Zhang</a><sup>1</sup>&emsp;
    <a href='https://songtaogithub.github.io/' target='_blank'>Songtao Lu</a><sup>2</sup>&emsp;
    <a href='https://zengfenghuang.github.io/' target='_blank'>Zengfeng Huang</a><sup>3</sup>&emsp;
    <a href='https://faculty.sist.shanghaitech.edu.cn/zhao/' target='_blank'>Ziping Zhao</a><sup>4</sup>
</div>
<div>
    <sup>1</sup>EPFL, <sup>2</sup>IBM Research, <sup>3</sup> FDU, <sup>4</sup> ShanghaiTech
</div>

</div>

## Abstract
Graph neural networks (GNNs) have made significant progress in various machine learning tasks.
Despite their success, many existing GNN models are shown to be vulnerable to adversarial attacks, creating a stringent need to build robust GNN architectures. 
In this work, we introduce a novel interpretable message passing scheme with adaptive structure (ASMP) to enhance the resilience of GNNs against graph structural attacks. 
The ASMP layers are constructed through optimization steps that concurrently optimize node features and graph structures, making the message passing process conducted across dynamically adjusted graphs at different layers. 
This adaptability enables ASMP to more effectively handle noisy or perturbed graph structures, thereby enhancing robustness. 
We also establish the theoretical convergence properties for the ASMP scheme. 
By integrating ASMP with neural networks, we introduce a new class of GNN models with adaptive structure (ASGNN).
Extensive experiments on semi-supervised node classification tasks demonstrate that ASGNN outperforms the state-of-the-art GNN architectures in terms of classification accuracy when subjected to various adversarial attack scenarios.

## Code
The code will be available soon.

## Citation

If you find our work useful in your research please consider citing our paper:

```
@article{zhang2024graph,
  title={Graph Neural Networks with Adaptive Structures},
  author={Zhang, Zepeng and Lu, Songtao and Huang, Zengfeng and Zhao, Ziping},
  journal={IEEE Journal of Selected Topics in Signal Processing},
  year={2024}
}
```
