# MAML implementation in PyTorch

## Introduction

This is a simple MAML implementation based on original paper and previous open-source implementations (listed in the references).  This can be used as a reference for MAML beginners, which is well annotated and easy to fine-tune.

## Running Results

You can take a look at some running results of this implementation at the following pages.

- [Omniglot 5way-5shot](https://www.kaggle.com/code/yeefaydu/maml-omniglot-5way-5shot)
- [Omniglot 5way-1shot](https://www.kaggle.com/code/yeefaydu/maml-omniglot-5way-1shot)

## Usage

To run this code, you can follow the instructions below.

1. Clone this repo.

```shell
git clone https://github.com/Yifei20/MAML-PyTorch.git
cd MAML-PyTorch
```

2. Download the [Omniglot](https://github.com/brendenlake/omniglot) dataset.

```shell
mkdir data
cd data
wget https://github.com/Yifei20/MAML-PyTorch/releases/download/dataset/Omniglot.zip
unzip Omniglot.zip
```

3. Run the code directly in the notebook, you can adjust the hyperparameter if you want.

## References

### Paper

- [Original Paper: Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](https://arxiv.org/abs/1703.03400)

### Github Repo

- [cbfnn/maml: Code of the Original Paper](https://github.com/cbfinn/maml)
- [Runist/torch_maml](https://github.com/Runist/torch_maml)

### Course Materials

- [NTU ML (Hung-Yi Lee), Spring 2023, HW15](https://speech.ee.ntu.edu.tw/~hylee/ml/2023-spring.php)

- [Standford CS 330: Deep Multi-Task and Meta Learning, Fall 2022, HW1](https://cs330.stanford.edu/fall2022/index.html)
