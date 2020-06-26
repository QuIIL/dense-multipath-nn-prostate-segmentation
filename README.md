# Deep Dense Multi-Path Neural Network For Prostate Segmentation In Magnetic Resonance Imaging [(Paper)](https://link.springer.com/article/10.1007/s11548-018-1841-4)
This repository contains the code for prostate segmentation in MRI using deep dense multi-path neural network. 

The Preprocessing and Augmentation pipeline are designed specifically for PROMISE12 dataset. However, they can be easily extended for using with other datasets.

The CNN Architecture proposed in our paper:
![alt text](https://media.springernature.com/full/springer-static/image/art%3A10.1007%2Fs11548-018-1841-4/MediaObjects/11548_2018_1841_Fig2_HTML.png?as=webp)

Our model achieved **95.11 DSC** on our private dataset when training on both T2 and MRI. 
![abc](https://media.springernature.com/full/springer-static/image/art%3A10.1007%2Fs11548-018-1841-4/MediaObjects/11548_2018_1841_Fig3_HTML.jpg?as=webp "On private dataset")

The PROMISE12 dataset contains heterogenous data from 4 different hospitals and institutes. All images were resampled to the spacing of (0.27, 0.27, 2.2) [x, y ,z].
The training set were split into the training* and validation sets based on the patient meta-data () to ensure that both the training* and validation sets contain data from all 4 hospitals/institues. The model achieved an average ~89 DSC without further post-processing.
A few examples of the model predictions on the validation set:

On the PROMISE12 dataset, we first 
To be updated...
