# Introduction-to-Machine-Learning Final Project

## Environment
* python: 3.10.5
* tesorflow: 2.11.0
* keras: 2.11.0

## How to reproduce the work
* First install following packages(for google colab)
```bash
!pip install keras
!pip install tensorflow
```
* To reproduce `109550135.csv`(file for submission) without retraining :
1. download [the pretrained model](https://drive.google.com/drive/folders/1bKJTxncll687Rdsdr0xXWU_3BLsR8fR0) 
2. run `109550139_Final_inference.ipynb`

## Train the model
After create the environment, you can run `109550139_Final_train.ipynb` to train the model.

The following structure is the CNN model structure:

![image](./README_img/summary.jpg)

Also, you can skip this step and directly use `109550139_Final_inference.ipynb` to evaluate the model performace.
>P.S. Since we save the trained model as `model.h5`, we need to download [the model](https://drive.google.com/drive/folders/1bKJTxncll687Rdsdr0xXWU_3BLsR8fR0) first, then run `109550139_Final_inference.ipynb`.

## Evaluate
Use `109550139_Final_inference.ipynb` to evaluate the model performace.

If you want to evaluate the model performance directly, you need to download [the model](https://drive.google.com/drive/folders/1bKJTxncll687Rdsdr0xXWU_3BLsR8fR0) first, then run `109550139_Final_inference.ipynb`.

## Results
After finishing `109550139_Final_inference.ipynb`, you will get `submission.csv`.

Here is the accuracy result:

![image](./README_img/submission.jpg)
| Submission         | Private Score   | Public Score   |
| ------------------ |---------------- | -------------- |
| 109550135.csv     |     0.59014     |      0.58504   |
