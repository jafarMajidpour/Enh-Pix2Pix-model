# Enh-Pix2Pix-model
# Enhanced Pix2Pix cGAN-based model
This paper presents Enhanced Pix2Pix (Enh-Pix2Pix), an advanced conditional generative adversarial network (cGAN) tailored for high-quality sparse-view CT image reconstruction.  Our methodology integrates many significant enhancements over the original Pix2Pix framework:  (1) an improved U-Net generator incorporating Xavier normal weight initialization, structured dropout regularization in the decoder layers, and gradient clipping to enhance training stability; and (2) an advanced PatchGAN discriminator employing Least Squares GAN (LSGAN) loss with a mean squared error formulation rather than binary cross-entropy for more stable adversarial training.  Comprehensive tests were performed on three medical datasets (LUNA16 and AbdomenCT-1K) using various sparse-view configurations (10, 16, 32, 64, 128, 256, and 512 projections) with 5-fold cross-validation.  
#
Dataset Available: 
AbdomenCT-1K dataset link: https://zenodo.org/records/5903769

LIDC-IDRI dataset link: https://www.cancerimagingarchive.net/collection/lidc-idri/

LUNA16 dataset link: https://www.kaggle.com/datasets/avc0706/luna16

#
![The Proposed Structure Image](Results/ProposedStructure.png)
