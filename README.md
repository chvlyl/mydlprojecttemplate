# My DL project template


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

The folder structure suggested by [PyTorch Template Project](https://github.com/victoresque/pytorch-template):
```
pytorch-template/
│
├── train.py - main script to start training
├── test.py - evaluation of trained model
├── config.json - config file
│
├── base/ - abstract base classes
│   ├── base_data_loader.py - abstract base class for data loaders
│   ├── base_model.py - abstract base class for models
│   └── base_trainer.py - abstract base class for trainers
│
├── data_loader/ - anything about data loading goes here
│   └── data_loaders.py
│
├── data/ - default directory for storing input data
│
├── model/ - models, losses, and metrics
│   ├── loss.py
│   ├── metric.py
│   └── model.py
│
├── saved/ - default checkpoints folder
│   └── runs/ - default logdir for tensorboardX
│
├── trainer/ - trainers
│   └── trainer.py
│
└── utils/
    ├── util.py
    ├── logger.py - class for train logging
    ├── visualization.py - class for tensorboardX visualization support
    └── ...
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

The following folder structure suggested by [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)

```
├── LICENSE                                                                                                                 
├── Makefile                                                                                                                
├── README.md                                                                                                               
├── data                                                                                                                    
│   ├── external                                                                                                            
│   ├── interim                                                                                                             
│   ├── processed                                                                                                           
│   └── raw                                                                                                                 
├── docs                                                                                                                    
│   ├── Makefile                                                                                                            
│   ├── commands.rst                                                                                                        
│   ├── conf.py                                                                                                             
│   ├── getting-started.rst                                                                                                 
│   ├── index.rst                                                                                                           
│   └── make.bat                                                                                                            
├── models                                                                                                                  
├── notebooks                                                                                                               
├── references                                                                                                              
├── reports                                                                                                                 
│   └── figures                                                                                                             
├── requirements.txt                                                                                                        
├── src                                                                                                                     
│   ├── __init__.py                                                                                                         
│   ├── data                                                                                                                
│   │   └── make_dataset.py                                                                                                 
│   ├── features                                                                                                            
│   │   └── build_features.py                                                                                               
│   └── model                                                                                                               
│       ├── predict_model.py                                                                                                
│       └── train_model.py                                                                                                  
└── tox.ini                  
```

## Reference
1. [CS230: Introducing the Project Code Examples](https://cs230-stanford.github.io/project-code-examples.html)
2. [CS230: Introduction to PyTorch Code Examples](https://cs230-stanford.github.io/pytorch-getting-started.html)
3. [Github CS230: Introduction to PyTorch Code Examples](https://github.com/cs230-stanford/cs230-code-examples/tree/master/pytorch/vision)
4. [PyTorch Project Template: Do it the smart way](https://www.linkedin.com/pulse/pytorch-project-template-do-smart-way-hager-rady/)
5. [Github PyTorch Project Template](https://github.com/moemen95/Pytorch-Project-Template)
6. [Deep Learning With PyTorch](https://medium.com/@josh_2774/deep-learning-with-pytorch-9574e74d17ad)
7. [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)
8. [Organizing machine learning projects: project management guidelines](https://www.jeremyjordan.me/ml-projects-guide/)
9. [How to Start a Data Science Project in Python](https://blog.godatadriven.com/how-to-start-a-data-science-project-in-python)
10. [Cookiecutter Data Science — Organize your Projects — Atom and Jupyter](https://medium.com/@rrfd/cookiecutter-data-science-organize-your-projects-atom-and-jupyter-2be7862f487e)
