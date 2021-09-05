# kaggle_code

## Models

- [Link](https://www.kaggle.com/fatihozturk/models-stacking-3rd-place-solution) 

This notebook is about how to use stack method to boost model performance. It lists three methods:

1. Stack models trained by different random seeds
2. transform regression problem into classification problem throught a threshold. Stack models trained by different threholds.

Tips: "lightGBM.train" function has a argument "init_model" which allows you to continue training a previous model using a smaller learning rate.

