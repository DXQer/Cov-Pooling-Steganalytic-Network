# Covariance-Pooling-Steganalytic-Network
A fast and eﬀective global covariance pooling network for image steganalysis in spatial domain.

## Abstract
Recently, deep learning based methods have achieved superior performance compared to conventional methods based on hand-crafted features in image steganalysis. However, most modern methods are usually quite time consuming. For instance, it takes over 3 days to train a state-of-the-art neural network, i.e. SRNet in our experiments. In this paper, therefore, we propose a fast yet very eﬀective convolutional neural network (CNN) for image steganalysis in spatial domain. To make a good tradeoﬀ between training time and performance, we carefully design the architecture of the proposed network according to our extensive experiments. In addition, we frst introduce the global covariance pooling into steganalysis to exploit the second-order statistic of high-level features for further improving the performance. Experimental results show that the proposed network can outperform the current best one, while its training time is signifcantly reduced.

## About dataset
The training, validation and test set are required to contain two catalogs: cover and stego. What's more, the stego images must have the same name as there corresponding cover images.

## About citation
Please cite the following paper if the code helps your research.

X. Deng, B. Chen, W. Luo and D. Luo, “Fast and Eﬀective Global Covariance Pooling Network for Image Steganalysis.” in Proceedings of the ACM Workshop on Information Hiding and Multimedia Security, 2019: 230-234.

## Reference
The MPNCOV includes the code about the implementation of global covariance pooling which is introduced in fast MPN-COV and its predecessor, i.e. MPN-COV.

P. Li, J. Xie, Q. Wang and Z. Gao, "Towards Faster Training of Global Covariance Pooling Networks by Iterative Matrix Square Root Normalization." The IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018.  
P. Li, J. Xie, Q. Wang and W. Zuo, "Is Second-Order Information Helpful for Large-Scale Visual Recognition?" The IEEE International Conference on Computer Vision (ICCV), 2017.
