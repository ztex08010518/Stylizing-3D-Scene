# Stylizing-3D-Scene
Coming soon :)

PyTorch implementaton of our WACV 2022 paper "Stylizing 3D Scene via Implicit Representation and HyperNetwork".
You can visit our project website [here](https://ztex08010518.github.io/3dstyletransfer/).

In this work, we aim to address the 3D scene stylization problem - generating stylized images of the scene at arbitrary novel view angles.

## Paper
[Stylizing 3D Scene via Implicit Representation and HyperNetwork](https://openaccess.thecvf.com/content/WACV2022/papers/Chiang_Stylizing_3D_Scene_via_Implicit_Representation_and_HyperNetwork_WACV_2022_paper.pdf)
[Pei-Ze Chiang]*(mailto:ztex080104518.cs08g@nctu.edu.tw), [Meng-Shiun Tsai]*(mailto:infinitesky.cs08g@nctu.edu.tw), [Hung-Yu Tseng](https://hytseng0509.github.io/), [Wei-Sheng Lai](https://www.wslai.net/), [Wei-Chen Chiu](https://walonchiu.github.io/)  
IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2022.

Please cite our paper if you find it useful for your research.  
```
@InProceedings{Chiang_2022_WACV,
    author    = {Chiang, Pei-Ze and Tsai, Meng-Shiun and Tseng, Hung-Yu and Lai, Wei-Sheng and Chiu, Wei-Chen},
    title     = {Stylizing 3D Scene via Implicit Representation and HyperNetwork},
    booktitle = {Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
    month     = {January},
    year      = {2022},
}
```

## Environment Setting
* This code was developed with Python 3.6.12 & Pytorch 1.6.0 & CUDA 10.0

## Testing

## Training and Dataset
1. Dataset: [Tanks and Temples](https://drive.google.com/file/d/15-4XEjFf7YAOh2ft9RC_DZew11YMjNCj/view?usp=sharing) and [Wikiart images](https://www.kaggle.com/c/painter-by-numbers)
2.  


## Acknowledgments
Our code is based on [NeRF++: Analyzing and Improving Neural Radiance Fields](https://github.com/Kai-46/nerfplusplus). 
The implementation of Hypternetwork is based on [Scene Representation Networks: Continuous 3D-Structure-Aware Neural Scene Representations](https://github.com/vsitzmann/scene-representation-networks).
The implementation of Consistency metric(Temporal Warping Error) is borrowed from [Learning Blind Video Temporal Consistency](https://github.com/phoenix104104/fast_blind_video_consistency).
