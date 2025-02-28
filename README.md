# Adaptive Knowledge Transfering with Switching Dual-Student Framework for Semi-Supervised Medical Image Segmentation
## Introduction
Official code for "[Adaptive Knowledge Transfering with Switching Dual-Student Framework for Semi-Supervised Medical Image Segmentation]".
## Usage
We provide `code`, `data_split` and `models` for LA and ACDC dataset.

Data could be got at [LA](https://github.com/yulequan/UA-MT/tree/master/data) and [ACDC](https://github.com/HiLab-git/SSL4MIS/tree/master/data/ACDC).

To train a model,
```
python LA_train.py  #for LA training
python ACDC_train.py --exp exp_name  #for ACDC training
``` 

To test a model,
```
python test_LA.py  #for LA testing
python test_ACDC.py --exp exp_name  #for ACDC testing
```



