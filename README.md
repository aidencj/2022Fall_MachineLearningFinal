# 2022Fall_MachineLearningFinal

## Environments
Python version: 3.7.12

Using this command to install packages

`pip install -r requirements.txt`

## Reproducing Submission
To reproduce my submission, please do the follow steps,

1. [Installation packages](#environments)
2. [Set path variable](#before-you-run-the-code)
3. To get model weights, you can either
  - Run 0811280_final_train.ipynb to generate model weights
  - [Download model weights](https://drive.google.com/drive/folders/1PUV47w0C8oUh-Qsj1FPbYUJ4heBZqP3z?usp=share_link)
4. Put model_weights.pth and 0811280_final_inference.ipynb in the same directory
5. Run 0811280_final_inference.ipynb to get submission.csv

## Before you run the code
Please do the following step before running.
### 0811280_final_train.ipynb
Change `INPUT_PATH = '/kaggle/input/tabular-playground-series-aug-2022/'` to the input data directory.
### 0811280_final_inference.ipynb
Change the following path to the input data directory and the model weights directory, respectively.
```
INPUT_PATH = '/kaggle/input/tabular-playground-series-aug-2022/'
MODEL_WEIGHT_PATH = '/kaggle/input/model-weights'
```
