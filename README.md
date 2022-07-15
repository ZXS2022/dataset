# dataset

Industrial Character Recognition Dataset built for our paper.

Our industrial character dataset consists of two main components, the real character dataset and the synthetic character dataset.

The detail of datasets is described in our paper and supplementary materials.

The structure of 'dataset' is as follows:

├── data_Synthetic  
│ 　　　  ├── label  ： labels for the training set, test set and validation set  
│ 　　　  └── raw  ：The output image by compositing  
└── data_real  
　　　　├── label  ：labels for the training set, test set and validation set  
　　　　├── original_image  ：Image before performing data enhancement  
　　　　└── raw  ：Image after data enhancement  

Please cite:
@article{XINSHENG2022103732,  
title = {Industrial character recognition based on improved CRNN in complex environments},  
journal = {Computers in Industry},  
volume = {142},   
pages = {103732},   
year = {2022},  
issn = {0166-3615},   
doi = {https://doi.org/10.1016/j.compind.2022.103732},  
url = {https://www.sciencedirect.com/science/article/pii/S0166361522001294},  
author = {Zhang XinSheng and Wang Yu},  
keywords = {Industrial character recognition, Squeeze-and-excitation, Residual structure, Gate recurrent unit},   
abstract = {Automatic character recognition is being gradually adopted in several everyday applications. In industrial settings, it can free up manpower required for reading and tracking product information. However, character recognition in industrial environments is particularly challenging. The main challenges are as follows: (1) There are no publicly available datasets that would aid the development of robust industrial character recognition methods; (2) Industrial characters may be printed in complex and uneven shapes on the surface of various materials, resulting in blurred characters, low contrast and distortion; (3) Industrial character recognition in complex industrial environments can suffers from various difficulties, such as uneven lighting conditions, oxidation of characters caused by long-term storage, etc. To address these challenges, we propose a convolutional recurrent neural network based on a residual structure and a “Squeeze-and-Excitation” block, namely RS-CRNN. The feature extraction of this method is inspired by ResNet and SEnet, and the method uses gate recurrent units for sequence label prediction. The model was trained and tested on constructed real and synthetic datasets, and experimental results show that the method has better performance than state-of-the-art character recognition models.}
}
