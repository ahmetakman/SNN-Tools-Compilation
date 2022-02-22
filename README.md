# SNN-Tools-Compilation
This repository intended to bring all software tools related spiking neural networks together.
This repository is being used as a notebook ,yet not completed. My personal first intuiton is, there are no library that takes cares of all kinds of learning configuration. Most of them focuses on specific type of learning method. However, when the SNNs becomes commercially avaliable in products we will find libraries like developed just for SNNs and includes all kinds of methods init.

LAVA-DL: github => https://github.com/lava-nc/lava-dl
Lava-dl (primarily in python) includes both ANN to SNN conversion method and direct training method. Also it is supported by Intel Labs (So, for the implenentation of loihi chips this might be a convinient choice.)

snnTorch: documentation => https://snntorch.readthedocs.io/en/latest/ github=> https://github.com/jeshraghian/snntorch
snn torch (only in python) is developed by Jason Eshraghian as an additive part of PyTorch which is one of the widely used ML/DL frameworks. 

Slayer (PyTorch): github=> https://github.com/bamsumit/slayerPytorch
This is the PyTorch (Python) port of the SLAYER approach on the SNN training. Detailed information can be found in the link.

Slayer (CUDNN): bitbucket => https://bitbucket.org/bamsumit/slayer/src/master/
This is the original (C++ and CUDNN framework) of the SLAYER approach on the SNN training. Detailed information can be found in the link.

STDP (PyTorch): github => https://github.com/guillaume-chevalier/Spiking-Neural-Network-SNN-with-PyTorch-where-Backpropagation-engenders-STDP
This is a hardcoded example of an SNN using STDP technique on PyTorch.

BindsNet (PyTorch): github => https://github.com/BindsNET/bindsnet
This is a SNN simulation library based on PyTorch (Python).

Norse (PyTorch): documentation => https://norse.github.io/norse/
Norse is also an expansion of PyTorch for neural structures.

SpyTorch (PyTorch): github => https://github.com/fzenke/spytorch
This is an implementation of surrogate gradient learning in spiking neural networks based on PyTorch.

For more similar works: https://github.com/norse/norse#4-similar-work
