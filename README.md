# Bad Tokens

Based on the work of https://github.com/Eric-Wallace/universal-triggers.

## Running

First install conda and make a python env. Then install the dependencies:

```
conda install conda-forge::transformers
conda install pytorch
```

To get running on a gpu, try the following instead of the pytorch line above:

```
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```
