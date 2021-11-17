# ToyCIFAR10

<<<<<<< HEAD
## Installation

```bash
conda create -n toycifar python=3.7
conda activate toycifar

# make sure that the pytorch cuda is consistent with the system cuda
# e.g., if your system cuda is 10.0, install torch 1.4 built from cuda 10.0
pip install torch==1.4.0+cu100 -f https://download.pytorch.org/whl/torch_stable.html

pip install -r requirements.txt
```

## Quick Start

1. Train

```bash
# start training a new network(vgg11 here)
python main.py --model vgg11
# resume training with pretrained model(vgg11 here)
python main.py --resume --model vgg11
```

2. Test

```bash
# test best pretrained model(vgg11 here)
python main.py --type test --model vgg11
```

## Training Details

=======

## Hyperparameter
>>>>>>> 1c5f465866a3060b36ea5f8ccb6af646682ffb35
### Learning Rate
| Model  | Learning Rate |
| :----: | :------: |
| VGG 11 |  0.1  |
| VGG 19 |  0.05  |

## Accuracy

| Model  | Accuracy |
| :----: | :------: |
| VGG 11 |  92.07%  |
| VGG 19 |  92.87%  |
