# Variational Diffusion Models

Implementation of [Variational Diffusion Models](https://arxiv.org/abs/2107.00630) in PyTorch. The original Jax/Flax code can be found [here](https://github.com/google-research/vdm).

## Standalone Colabs

At `SimpleDiffusionColab_PyTorch.ipynb` you will find an independent and stand-alone Colab implementation of a Variational Diffusion Model (VDM), serving as an easy-to-understand demonstration of the code and principles behind the paper. [Link to open in Colab](https://colab.research.google.com/github/ehonig/vdm-pytorch/blob/main/SimpleDiffusionColab_PyTorch.ipynb). (Thanks a lot to [Alex Alemi](https://www.alexalemi.com/) and [Ben Poole](https://cs.stanford.edu/~poole/) for the original implementation of this.)

At `2D_VDM_Example_PyTorch.ipynb` you will find a basic implementation, on a 2D swirl dataset and using MLPs. [Link to open in Colab](https://colab.research.google.com/github/ehonig/vdm-pytorch/blob/main/2D_VDM_Example_PyTorch.ipynb).

## Todo

- [X] 2D swirl Notebook
- [X] EMNIST Notebook
- [ ] model_vdm.py

## Citations

```bibtex
@article{kingma2021variational,
  title={Variational diffusion models},
  author={Kingma, Diederik and Salimans, Tim and Poole, Ben and Ho, Jonathan},
  journal={Advances in neural information processing systems},
  volume={34},
  pages={21696--21707},
  year={2021}
}

@incollection{NEURIPS2019_9015,
  title = {PyTorch: An Imperative Style, High-Performance Deep Learning Library},
  author = {Paszke, Adam and Gross, Sam and Massa, Francisco and Lerer, Adam and Bradbury, James and Chanan, Gregory and Killeen, Trevor and Lin, Zeming and Gimelshein, Natalia and Antiga, Luca and Desmaison, Alban and Kopf, Andreas and Yang, Edward and DeVito, Zachary and Raison, Martin and Tejani, Alykhan and Chilamkurthy, Sasank and Steiner, Benoit and Fang, Lu and Bai, Junjie and Chintala, Soumith},
  booktitle = {Advances in Neural Information Processing Systems 32},
  pages = {8024--8035},
  year = {2019},
  publisher = {Curran Associates, Inc.},
  url = {http://papers.neurips.cc/paper/9015-pytorch-an-imperative-style-high-performance-deep-learning-library.pdf}
}
```
