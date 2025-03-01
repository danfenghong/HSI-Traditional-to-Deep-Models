The repository contains the implementations for [Hyperspectral Image Classification -- Traditional to Deep Models: A Survey for Future Prospects](https://arxiv.org/abs/2101.06116).

<img src="HSI_App.png"/>

## Models

Currently, the following traditional machine learning methods are available:

- [x] [RF](https://ieeexplore.ieee.org/document/1396322)  
- [x] [MLR](https://ieeexplore.ieee.org/document/5559437)
- [x] [SVM](https://ieeexplore.ieee.org/document/1323134) 
- [x] [MLP](https://www.sciencedirect.com/science/article/pii/S0924271619302187)
- [x] [RNN](https://ieeexplore.ieee.org/document/8662780)
- [x] [LSTM](https://colah.github.io/posts/2015-08-Understanding-LSTMs)
- [x] [GRU](https://arxiv.org/abs/1409.1259v2)

Currently, the following deep learning methods are available:

- [x] [CNN-1D](https://www.sciencedirect.com/science/article/pii/S0924271619302187)
- [x] [CNN-2D](https://ieeexplore.ieee.org/document/7326945)
- [x] [CNN-3D](https://ieeexplore.ieee.org/document/8344565)
- [x] [HybridSN](https://ieeexplore.ieee.org/document/8736016)
- [x] [MorphCNN](https://ieeexplore.ieee.org/document/9451651)
- [x] [GCN](https://ieeexplore.ieee.org/document/9170817)

Currently, the following convolutional feature extraction methods are available:

- [x] [G2C-Conv2D](https://ieeexplore.ieee.org/document/9570352)
- [x] [G2C-Conv3D](https://ieeexplore.ieee.org/document/9570352)


If you have questions or suggestions, please feel free to open an issue. Please cite as:
```
@article{ahmad2021hyperspectral,
  title     = {Hyperspectral Image Classification--Traditional to Deep Models: A Survey for Future Prospects},
  author    = {Muhammad Ahmad, and Sidrah Shabbir, and Swalpa Kumar Roy, and Danfeng Hong, and Xin Wu, and Jing Yao, and Adil Mehmood Khan, and Manuel Mazzara, and Salvatore Distefano, and Jocelyn Chanussot},
  journal   = {IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year      = {2022},
  volume    = {15},
  pages     = {968--999},
  note      = {DOI: 10.1109/JSTARS.2021.3133021},
  publisher = {IEEE}
}
```

## Acknowledgement

Part of this code is from a implementation of Classification of HSI using CNN by [BehnoodRasti](https://github.com/BehnoodRasti/HyFTech-Hyperspectral-Shallow-Deep-Feature-Extraction-Toolbox) and [mhaut](https://github.com/mhaut/hyperspectral_deeplearning_review).
