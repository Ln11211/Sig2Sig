# Sig2Sig
Sig2Sig is OFDM Channel estimator and equalizer based on the Pix2Pix architecture. This is a Deep learning approach for Channel estimation problem in wireless communication.

# What is Channel Estimation?

Channels fade in time and frequency.
Channel estimation refers to the process of estimating the characteristics of the wireless channel between the transmitter and receiver. Equalization is the process of equalizing the channel fadign effect using the estimated channel.

## Channel fading occurs due to multihop transmission, doppler shift effect, etc
![image](https://github.com/user-attachments/assets/8a50f221-3e60-4e5d-85c0-ba090cf717d7)

## Estimation and Equalisation are simple mathematical operations, represented as follows:
![image](https://github.com/user-attachments/assets/31723993-225b-4f59-ae92-5bfe3f6518b7)
![image](https://github.com/user-attachments/assets/23156198-0d0f-4cb9-b3d5-861f93653ab1)

# Sig2Sig Architecture

Sig2Sig is a Deep Learning Architecture for Channel estimation and equalization.In the Deep Learning method we consider the time-frequency response of a fading communication channel as a two-dimensional image.
 
![image](https://github.com/user-attachments/assets/36051326-ae69-4579-ad12-fb4850134074)

Internal components of the Sig2Sig architecture

![image](https://github.com/user-attachments/assets/674076a7-152c-4772-a003-ca8e5d9b1e6d)

Generator and Discriminator architecures of Sig2Sig

![image](https://github.com/user-attachments/assets/6a9c0940-c8cd-40e1-9c93-8ca66088cb4c)

Layers in the Sig2Sig model
![image](https://github.com/user-attachments/assets/176d90c8-2ab4-4ab2-821a-4f285d4c75f1)


The output of the model is as follows:

![image](https://github.com/user-attachments/assets/b1150776-a853-4319-b54a-f5f77ab1cb70)


# Channel Fading Dataset
The dataset used for this problem is taken from Mehran Soltani, et.al. one sample is shown below,
![image](https://github.com/user-attachments/assets/4de88619-a4f0-4a09-91f7-18b4bc48145a)
Dataset is hosted on Kaggle.

Kaggle dataset link:- https://www.kaggle.com/datasets/malyala11211/ofdmdataset-mehransoltani/data

https://www.kaggle.com/datasets/malyala11211/mehran-multi-db/data

# Notebooks

The models are trained in kaggle. Notebook links:

Sig2Sig trial 2:- https://www.kaggle.com/code/malyala11211/sig2sig-trial-2

Sig2Sig (first version, no comments)- https://www.kaggle.com/code/malyala11211/sig2sig

Sig2Sig Benchmarking :- https://www.kaggle.com/code/malyala11211/sig2sig-benchmarking
