# LACNN

This code is for our paper "Attention to Lesion: Lesion-Aware Convolutional Neural Network for Retinal Optical Coherence Tomography Image Classification". If you use this code, please consider to cite the following paper:

L. Fang, C. Wang, S. Li, H. Rabbani, X. Chen and Z. Liu, "Attention to Lesion: Lesion-Aware Convolutional Neural Network for Retinal Optical Coherence Tomography Image Classification," IEEE Transactions on Medical Imaging, 2019.

If you have any questions, please contact us, E-mail: fangleyuan@gmail.com or chongwang@hnu.edu.cn

Requirements: tensorflow 1.3+, python 2.7.

Usage:
(1) create folder '/Model/LDN' in the current dir, download the LDN mdoel [here](), and put the downloaded model in './LACNN/Model/LDN'

(2) run Generate_attenmap.py to create attention maps for the UCSD dataset

(3) run LACNN_train.py to train LACNN, VGG16.npy file can be found in [here](https://github.com/machrisaa/tensorflow-vgg)                                                                                                                                                                                                                                                                                                                                                                                           

(4) run LACNN_test.py to test LACNN
