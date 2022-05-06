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
