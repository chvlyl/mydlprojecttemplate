# mydlprojecttemplate
My DL project template


The folder structure suggested by CS230 course:
```
data/
    train/
    dev/
    test/
experiments/
model/
    *.py
build_dataset.py
train.py
search_hyperparams.py
synthesize_results.py
evaluate.py
```

The following folder structure suggested by [Github PyTorch Project Template](https://github.com/moemen95/Pytorch-Project-Template)
```
├── agents
|  └── dcgan.py
|  └── condensenet.py
|  └── mnist.py
|  └── dqn.py
|  └── example.py
|  └── base.py
|  └── erfnet.py
|
├── configs
|  └── dcgan_exp_0.py
|  └── condensenet_exp_0.py
|  └── mnist_exp_0.py
|  └── dqn_exp_0.py
|  └── example_exp_0.py
|  └── erfnet_exp_0.py
|
├── data
|
├── datasets
|  └── cifar10.py
|  └── celebA.py
|  └── mnist.py
|  └── example.py
|  └── voc2012.py
|
├── experiments
|
├── graphs
|  └── models
|  |  └── custome_layers
|  |  |  └── denseblock.py
|  |  |  └── layers.py
|  |  |
|  |  └── dcgan_discriminator.py
|  |  └── dcgan_generator.py
|  |  └── erfnet.py
|  |  └── erfnet_imagenet.py
|  |  └── condensenet.py
|  |  └── mnist.py
|  |  └── dqn.py
|  |  └── example.py
|  |
|  └── losses
|  |  └── loss.py
|
├── pretrained_weights
|
├── tutorials
|
├── utils
|  └── assets
|
├── main.py
└── run.sh
```

## Reference
1. [CS230: Introducing the Project Code Examples](https://cs230-stanford.github.io/project-code-examples.html)
2. [CS230: Introduction to PyTorch Code Examples](https://cs230-stanford.github.io/pytorch-getting-started.html)
3. [Github CS230: Introduction to PyTorch Code Examples](https://github.com/cs230-stanford/cs230-code-examples/tree/master/pytorch/vision)
4. [PyTorch Project Template: Do it the smart way](https://www.linkedin.com/pulse/pytorch-project-template-do-smart-way-hager-rady/)
5. [Github PyTorch Project Template](https://github.com/moemen95/Pytorch-Project-Template)
6. [Deep Learning With PyTorch](https://medium.com/@josh_2774/deep-learning-with-pytorch-9574e74d17ad)
