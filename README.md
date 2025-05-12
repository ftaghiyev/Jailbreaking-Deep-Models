# Jailbreaking Deep Models

A comprehensive implementation of adversarial attacks on ImageNet classifiers, demonstrating the vulnerability of deep neural networks to carefully crafted perturbations.

## Overview

This project implements and evaluates three types of adversarial attacks on state-of-the-art image classifiers:
- Fast Gradient Sign Method (FGSM)
- Projected Gradient Descent (PGD)
- Localized Patch Attacks

The attacks are tested on ResNet-34 and DenseNet-121 models trained on ImageNet-1K, showing how even small perturbations can significantly degrade model performance.

## Features

- Implementation of FGSM, PGD, and patch-based adversarial attacks
- Support for both ResNet-34 and DenseNet-121 architectures
- Comprehensive evaluation metrics including top-1 and top-5 accuracy
- Visualization tools for comparing original and adversarial examples

## Installation

```bash
# Clone the repository
git clone https://github.com/ftaghiyev/Jailbreaking-Deep-Models.git
cd Jailbreaking-Deep-Models

# Install dependencies
pip install -r requirements.txt
```

## Results

Our experiments demonstrate significant degradation in model performance across all attack methods. For detailed results and analysis, please refer to the [full report](jailbreaking_deep_models.pdf).

