fmnist_demos
===
PyTorch demos on [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) datasets.

Starting from [the PyTorch official beginner tutorial](https://pytorch.org/tutorials/beginner/basics/intro.html), we have following ready-to-play Jupyter notebooks for different models:
- `pytorch-quickstart.ipynb`: Quickstart tutorial model from the PyTorch website.
- `residual_net.ipynb`: A simple model built with the residual block proposed in [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385v1).
- `autoencoder.ipynb`: Residual net auto encoder model to reconstruct the input image.
- `vq-vae.ipynb`: Re-implementation of Variational AutoEncoder (VQ-VAE) model proposed in [Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937).

## License
Copyright (c) 2024 Mengxiao Lin<linmx0130@gmail.com>
See LICENSE file. 

## Citation
If you use some of the code in your experiments, please cite the original papers which proposes those models:
```
@online{xiao2017/online,
  author       = {Han Xiao and Kashif Rasul and Roland Vollgraf},
  title        = {Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms},
  date         = {2017-08-28},
  year         = {2017},
  eprintclass  = {cs.LG},
  eprinttype   = {arXiv},
  eprint       = {cs.LG/1708.07747},
}
@inproceedings{he2016deep,
  title={Deep residual learning for image recognition},
  author={He, Kaiming and Zhang, Xiangyu and Ren, Shaoqing and Sun, Jian},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={770--778},
  year={2016}
}
@article{van2017neural,
  title={Neural discrete representation learning},
  author={Van Den Oord, Aaron and Vinyals, Oriol and others},
  journal={Advances in neural information processing systems},
  volume={30},
  year={2017}
}
``` 
