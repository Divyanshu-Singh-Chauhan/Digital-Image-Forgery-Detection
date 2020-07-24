# Image-Forgery-Detection

"master" branch contains Non-DL approaches and "DL" branch contains DL approaches.

Models for Digital Image Forgery Detection.

This contains all the models built using Deep Learning approaches.
The Dataset used for all the models was CASIA2 Dataset.

DL_Simple1 - For Detection of forgery only - Needs a lot of improvement.

UNET - For Localisation of forgery using ELA and its masks as the dataset.
1. UNET_MODEL - Contains the standard model with no augmentations and input as ELA converted Images 
2. UNET_FINAL_TEST_MODEL - Containa the model with addition of custom layer, batchnorm, and input is 1,2,4 channeled ( ELA only, ELA + Grayscale, ELA + RGB )

Data_Preprocessing - Contains the code for prerprocessing of the CASIA2 dataset.

GANs Based Autoencoder :-
This contains the GANs aided Autoencoder model built to detect forgery in images using self-supervised learning approach.
Reference from : https://arxiv.org/pdf/1802.04881.pdf - Satellite Image Forgery Detection
