# Hierarchical Uncertainty Fusion and Calibration for Reliable Cell Image Classification under Domain Shift
 
Official implementation of the paper:
 
> Hierarchical Uncertainty Fusion and Calibration for Reliable Cell Image Classification under Domain Shift
 
## Overview
 
This repository provides the implementation of a hierarchical uncertainty fusion framework for reliable cell image classification under domain shift.
 
## Requirements
 
- Python 3.10+
- PyTorch 2.0+
- CUDA 11.x
 
Install dependencies:
 
```bash
pip install -r requirements.txt
```
 
## Datasets
 
The three public datasets can be downloaded from the links provided in **img.md**.
 
After downloading, organize the datasets as:
 
```
datasets/
├── SIPaKMeD/
├── HEp2/
└── Herlev/
```
 
## Training
 
```bash
python train.py
```
 
## Testing
 
```bash
python test.py
```
 
## Acknowledgement
 
We thank the authors of the public datasets used in this work.

The complete source code will be publicly released upon acceptance of the paper.
