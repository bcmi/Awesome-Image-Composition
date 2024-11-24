# Awesome Image Composition  ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)


A curated list of resources including papers, datasets, and relevant links pertaining to image composition (object insertion). **The goal of image composition is inserting one foreground into a background image to get a realistic composite image, by addressing the inconsistencies (appearance, geometry, and semantic inconsistency) between foreground and background.** Generally speaking, image composition could be used to combine the visual elements from different images.

Welcome to follow WeChat public account ["Newly AIGCer"](https://www.ustcnewly.com/blog.html) or Zhihu Column ["Newly CVer"](https://www.zhihu.com/column/c_1333918224900206592) to get the latest information about image composition! 

<div align="center">
</br>
<img src="https://raw.githubusercontent.com/bcmi/libcom/main/resources/image_composition_task.gif" width="600" />
</div>

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Online Demo](#Online-demo)
+ [Survey](#Survey)
+ [Toolbox](#Toolbox)
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Evaluation](#Evaluation)

## Online Demo

Try this [online demo](https://bcmi.sjtu.edu.cn/home/niuli/demo_image_composition/) for image composition and have fun! ![hot](https://bcmi.sjtu.edu.cn/~niuli/images/fire.png)

## Survey
+ Li Niu, Wenyan Cong, Liu Liu, Yan Hong, Bo Zhang, Jing Liang, Liqing Zhang: "*Making Images Real Again: A Comprehensive Survey on Deep Image Composition.*" arXiv preprint arXiv:2106.14490 (2021). [[arXiv]](https://arxiv.org/pdf/2106.14490.pdf) [[slides]](https://www.ustcnewly.com/download/Image_composition_tutorial.pdf)


## Toolbox
We integrate 10+ image composition related functions into [libcom](https://github.com/bcmi/libcom) (the library of image composition), including image blending, standard/painterly image harmonization, shadow generation, object placement, generative composition, quality evaluation, etc. The ultimate goal of this library is solving all the problems related to image composition with simple `import libcom`.  



## Papers

#### 1. Image Blending
  &emsp;  [Awesome-Image-Blending](https://github.com/bcmi/Awesome-Image-Blending)

#### 2. Image Harmonization
  &emsp;  [Awesome-Image-Harmonization](https://github.com/bcmi/Awesome-Image-Harmonization)
 
#### 3. Object Shadow Generation

  &emsp;  [Awesome-Object-Shadow-Generation](https://github.com/bcmi/Awesome-Object-Shadow-Generation)
  
#### 4. Object Reflection Generation
+ Daniel Winter, Matan Cohen, Shlomi Fruchter, Yael Pritch, Alex Rav-Acha, Yedid Hoshen: "*ObjectDrop: Bootstrapping Counterfactuals for Photorealistic Object Removal and Insertion.*"  ECCV (2024) [[pdf]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09857.pdf)
+ Gemma Canet Tarrés, Zhe Lin, Zhifei Zhang, Jianming Zhang, Yizhi Song, Dan Ruta, Andrew Gilbert, John Collomosse, Soo Ye Kim："*Thinking Outside the BBox: Unconstrained Generative Object Compositing.*" ECCV (2024) [[pdf]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07965.pdf)
+ Shengjie Ma, Qian Shen, Qiming Hou, Zhong Ren, Kun Zhou: "*Neural Compositing for Real-time Augmented Reality Rendering in Low-frequency Lighting Environments.*" Science China Information Sciences (2021) [[pdf]](http://kunzhou.net/2021/NeuralComposite.pdf)
  
#### 5. Object Placement 

  &emsp;  [Awesome-Object-Placement](https://github.com/bcmi/Awesome-Object-Placement)

#### 6. Perspective Transformation
+ Junhong Gou, Bo Zhang, Li Niu, Jianfu Zhang, Jianlou Si, Chen Qian, Liqing Zhang: "*Virtual Accessory Try-On via Keypoint Hallucination.*" arXiv preprint arXiv:2310.17131 (2023) [[arXiv]](https://arxiv.org/pdf/2310.17131.pdf)
+ Bo Zhang, Yue Liu, Kaixin Lu, Li Niu, Liqing Zhang: "*Spatial Transformation for Image Composition via Correspondence Learning.*" arXiv preprint arXiv:2207.02398 (2022) [[arXiv]](https://arxiv.org/pdf/2207.02398.pdf)
+ Fangneng Zhan, Hongyuan Zhu, Shijian Lu: "*Spatial Fusion GAN for Image Synthesis.*" CVPR (2019) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhan_Spatial_Fusion_GAN_for_Image_Synthesis_CVPR_2019_paper.pdf) 
+ Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey: "*ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing.*" CVPR (2018) [[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Lin_ST-GAN_Spatial_Transformer_CVPR_2018_paper.pdf) [[code]](https://github.com/chenhsuanlin/spatial-transformer-GAN)

#### 7. Occlusion
+ Lingxiao Li, Kaixiong Gong, Weihong Li, Xili Dai, Tao Chen, Xiaojun Yuan, Xiangyu Yue: "*BIFRÖST: 3D-Aware Image compositing with Language Instructions.*" NeurIPS (2024) [[arXiv]](https://arxiv.org/pdf/2410.19079) [[code]](https://github.com/lingxiao-li/Bifrost)
+ Jonghyun Lee, Hansam Cho, Youngjoon Yoo, Seoung Bum Kim, Yonghyun Jeong: "*Compose and Conquer: Diffusion-Based 3D Depth Aware Composable Image Synthesis.*" ICLR (2024) [[pdf]](https://arxiv.org/html/2401.09048v1) [[code]](https://github.com/tomtom1103/compose-and-conquer)
+ Zan Li, Wencheng Wang, Fei Hou: "*Image Composition with Depth Registration.*" IJCAI (2023) [[paper]](https://www.ijcai.org/proceedings/2023/0126.pdf)
+ Fangneng Zhan, Jiaxing Huang, Shijian Lu: "*Hierarchy Composition GAN for High-fidelity Image Synthesis.*" Transactions on cybernetics (2021) [[arXiv]](https://arxiv.org/pdf/1905.04693.pdf)
+ Samaneh Azadi, Deepak Pathak, Sayna Ebrahimi, Trevor Darrell: "*Compositional GAN: Learning Image-Conditional Binary Composition.*" IJCV (2020) [[arXiv]](https://arxiv.org/pdf/1807.07560.pdf) [[code]](https://github.com/azadis/CompositionalGAN)

#### 8. Resolution/Sharpness/Noise Discrepancy

+ Jizhizi Li, Jing Zhang, Stephen J.Maybank, Dacheng Tao: "*Bridging Composite and Real: Towards End-to-End Deep Image Matting.*" IJCV (2021) [[pdf]](https://link.springer.com/content/pdf/10.1007/s11263-021-01541-0.pdf) [[code]](https://github.com/JizhiziLi/GFM)

#### 9. Foreground Object Search

  &emsp;  [Awesome-Foreground-Object-Search](https://github.com/bcmi/Awesome-Foreground-Object-Search)

#### 10. Generative Image Composition

  &emsp;  [Awesome-Generative-Image-Composition](https://github.com/bcmi/Awesome-Generative-Image-Composition) 

## Datasets
+ Datasets for image harmonization [[link]](https://github.com/bcmi/Awesome-Image-Harmonization#Datasets)
+ Datasets for object shadow generation [[link]](https://github.com/bcmi/Awesome-Object-Shadow-Generation#Datasets)
+ Datasets for object placement [[link]](https://github.com/bcmi/Awesome-Object-Placement#Datasets)
+ Datasets for foreground object search [[link]](https://github.com/bcmi/Awesome-Foreground-Object-Search/tree/main#Datasets)
+ Datasets for perspective transformation [[link]](https://github.com/bcmi/Accessory-Try-On-Dataset-STRAT)
+ Datasets for generative image composition [[link]](https://github.com/bcmi/Awesome-Generative-Image-Composition?tab=readme-ov-file#Test-set)

## Evaluation

+ [Composite-Image-Evaluation](https://github.com/bcmi/Composite-Image-Evaluation)

