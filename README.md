# Hust_Deep
#**Unsupervised Domain Adaptation Using Generative Adversarial Networks for Semantic Segmentation of Aerial Images**
## Introduction
This repo contains our project in *Deep learning* subject at Hanoi University of Science and Technology  

Nhóm sử dụng các mô hình Unet để phân đoạn ảnh trên tập Potsdam rồi sử dụng CyCGan để chuyển các ảnh của tập dữ liệu Potsdam thành định dạng giống với tập ảnh Vaihingen. Sau đó dùng các ảnh đã được truyển đổi để fine-tuning các mạng Unet đã được train trước đó rồi thực nghiệm chúng với kết quả trên tập Vaihingen
 
 
## Contribute
+ Võ Minh Trí - 20210862 - KHMT K66
+ Vũ Trịnh Kim - 20215409 - KHMT K66
+ Nguyễn Đức Thinh - 20210817 - KHMT K66

## Table of contents
1. [Introduction](#Introduction)
2. [Contribute](#Contribute)
3. [Requirement](#Dependencies)
4. [Installation](#INSTALLATION)
5. [Quick use](#QUICK-USE)
6. [Data visualization and preprocessing data](#DATA-VISUALIZATION-AND-ENCODING-DATA)
## Requirement
**Programming language**: Python version 3.8 or greater  
**Library**: scikit-learn, tensorflow, keras, matplotlib, pandas, numpy, seaborn, joblib 
## Installation
Import library
```
pip install -U scikit-learn
pip install tensorflow
pip install keras
pip install matplotlib
pip install pandas
pip install numpy
pip install seaborn
pip install joblib
```
## Quick use
```
cd code
```
Run each algorithm respectively in these files below:
[Unet](https://github.com/trito11/Hust_Deep/blob/main/unet-deep.ipynb)

[Banet](https://github.com/trito11/Hust_Deep/blob/main/banet1.ipynb)

[Manet](https://github.com/trito11/Hust_Deep/blob/main/manet-deep.ipynb))

[UnetFormer](https://github.com/trito11/Hust_Deep/blob/main/unet-former.ipynb))

[Unetplusplu](https://github.com/trito11/Hust_Deep/blob/main/unetplusplus.ipynb)

[Upernet](https://github.com/trito11/Hust_Deep/blob/main/upernet.ipynb)
[CycGan](https://github.com/trito11/Hust_Deep/blob/main/ccgan-unet.ipynb)

## Data 
[Data](https://www.kaggle.com/datasets/trito12/deep-data-potsdam-vaihingen)
