<img width="725" alt="image" src="https://github.com/GabyUSTC/DIRL/assets/47773237/629f544c-88b9-48fc-bfde-c265cbe9c8b0"># Discriminative-Invariant Representation Learning for Unbiased Recommendation

## Introduction

In this project, we provide a novel discriminative-invariant representation learning (DIRL) method for unbiased recommendation.

## Environment

We provide the environment that our code depends on in DIRL_env.ymal. To install the conda environment, run
```bash
conda env create -f DIRL_env.ymal
```

## Dataset

1. Each line contains user ID, item ID, and label type (i.e., positve or negative).
2. We split Yahoo!R3 for training, validation, and testing (i.e., yahooR3t4p5_train for training, uni_yahooR3t4p5_val for validation, and uni_yahooR3t4p5_test for testing).

## Run the Code

```bash
python main.py --data_name=yahooR3
```
