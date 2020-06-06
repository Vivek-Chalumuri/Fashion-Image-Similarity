# Data Science Project
This project is aimed to implement methods to identify similar fashion images. We do this by applying the methods described in the paper [Learning visual similarity for product design with convolutional neural networks](https://dl.acm.org/doi/pdf/10.1145/2766959). 


# Commands
------------------
1. Download the image data
```bash
$ scripts/download_deepfashion_ds.sh
```
2. Build the metadata csv
```bash
$ scripts/create_deepfashion_meta.py
```
3. Train specific model
```bash
$ python train_siamcat.py
```
