# FitTrex
Code for FitTrex

How to use inference.py:

Step 1: Install basic python packages

pip install torch, torchvision, PIL, numpy, matplotlib, argparse

Step 2: Clone the entire repo, put the file in the GitHub repo folder, and run the inference script as below.

python inference.py -model=resnet18_food101_state_dict -label=food101_labels.txt -img=burger.jpg

Parameters:
-model: the path to the PyTorch dictionary file you want to load
-label: the path to the labels of the food dataset
-img: the path to the image you want to run inference on

Be sure to download the following files if you don't clone the repo:
(1) resnet18_food101_state_dict
(2) food101_labels.txt
