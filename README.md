# Awesome Image Composition  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources including papers, datasets, and relevant links pertaining to image composition.

## Contributing

Contributions are welcome.  If you wish to contribute, feel free to send a pull request. If you have suggestions for new sections to be included, please raise an issue and discuss before sending a pull request.

## Table of Contents
+ [Papers](#Papers)
+ [Datasets](#Datasets)
+ [Other Resources](#Other-resources)
+ [Related Topics](#Related-topics)


## Papers

#### Image blending
+ Huikai Wu, Shuai Zheng, Junge Zhang, Kaiqi Huang: "*GP-GAN: Towards Realistic High-Resolution Image Blending.*" ACM MM (2019) [[arXiv]](https://arxiv.org/pdf/1703.07195.pdf) [[code]](https://github.com/wuhuikai/GP-GAN)
+ Lingzhi Zhang, Tarmily Wen, Jianbo Shi: "*Deep Image Blending.*" WACV (2020) [[pdf]](https://openaccess.thecvf.com/content_WACV_2020/papers/Zhang_Deep_Image_Blending_WACV_2020_paper.pdf) [[arXiv]](https://arxiv.org/pdf/1910.11495.pdf) [[code]](https://github.com/owenzlz/DeepImageBlending)

#### Image harmonization
+ Wenyan Cong, Li Niu, Jianfu Zhang,  Jing Liang, Liqing Zhang: "*BargainNet: Background-Guided Domain Translation for Image Harmonization.*" ICME (2021) [[arXiv]](https://arxiv.org/abs/2009.09169) [[code]](https://github.com/bcmi/BargainNet).
+ Konstantin Sofiiuk, Polina Popenova, Anton Konushin: "*Foreground-aware Semantic Representations for Image Harmonization.*" WACV (2021) [[pdf]](https://openaccess.thecvf.com/content/WACV2021/papers/Sofiiuk_Foreground-Aware_Semantic_Representations_for_Image_Harmonization_WACV_2021_paper.pdf) [[supp]](https://openaccess.thecvf.com/content/WACV2021/supplemental/Sofiiuk_Foreground-Aware_Semantic_Representations_WACV_2021_supplemental.zip)  [[arXiv]](https://arxiv.org/abs/2006.00809) [[code]](https://github.com/saic-vul/image_harmonization)
+ Guoqing Hao, Satoshi Iizuka, Kazuhiro Fukui: "*Image Harmonization with Attention-based Deep Feature Modulation*." BMVC (2020) [[pdf]](https://www.bmvc2020-conference.com/assets/papers/0121.pdf) [[supp]](https://www.bmvc2020-conference.com/assets/supp/0121_supp.zip) [[code]](https://github.com/Dominoer/bmvc2020_image_harmonization)
+ Wenyan Cong, Jianfu Zhang, Li Niu, Liu Liu, Zhixin Ling, Weiyuan Li, Liqing Zhang: "*DoveNet: Deep Image Harmonization via Domain Verification.*" CVPR (2020) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cong_DoveNet_Deep_Image_Harmonization_via_Domain_Verification_CVPR_2020_paper.pdf) [[supp]](https://openaccess.thecvf.com/content_CVPR_2020/supplemental/Cong_DoveNet_Deep_Image_CVPR_2020_supplemental.pdf) [[arXiv]](https://arxiv.org/abs/1911.13239) [[code]](https://github.com/bcmi/Image_Harmonization_Datasets/tree/master/DoveNet).
+ Xiaodong Cun, Chi-Man Pun: "*Improving the Harmony of the Composite Image by Spatial-Separated Attention Module.*" IEEE Trans. Image Process. 29: 4759-4771 (2020) [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9018370) [[arXiv]](https://arxiv.org/abs/1907.06406) [[code]](https://github.com/vinthony/s2am)
+ Yi-Hsuan Tsai, Xiaohui Shen, Zhe Lin, Kalyan Sunkavalli, Xin Lu, Ming-Hsuan Yang: "*Deep Image Harmonization.*" CVPR (2017) [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tsai_Deep_Image_Harmonization_CVPR_2017_paper.pdf) [[supp]](http://vllab.ucmerced.edu/ytsai/CVPR17/cvpr17_harmonization_supp.pdf) [[arXiv]](https://arxiv.org/abs/1703.00069) [[code]](https://github.com/wasidennis/DeepHarmonization)

#### Shadow generation
+ Daquan Liu, Chengjiang  Long, Hongpan Zhang, Hanning Yu, Xinzhi  Dong, Chunxia Xiao: "*Arshadowgan: Shadow generative adversarial network for augmented reality in single light scenes.*" CVPR (2020) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_ARShadowGAN_Shadow_Generative_Adversarial_Network_for_Augmented_Reality_in_Single_CVPR_2020_paper.pdf) [[code]](https://github.com/ldq9526/ARShadowGAN).

+ Shuyang Zhang, Runze Liang, Miao Wang: "*Shadowgan: Shadow synthesis for virtual objects with conditional adversarial networks.*" Computational Visual Media (2019) [[pdf]](https://link.springer.com/content/pdf/10.1007/s41095-019-0136-1.pdf).

+ Fangneng Zhan, Shijian Lu, Changgong Zhang, Feiying Ma, Xuansong Xie: "*Adversarial Image Composition with Auxiliary Illumination.*" ACCV (2020) [[pdf]](https://openaccess.thecvf.com/content/ACCV2020/papers/Zhan_Adversarial_Image_Composition_with_Auxiliary_Illumination_ACCV_2020_paper.pdf).

#### Object placement and spatial transformation
+ Lingzhi Zhang, Tarmily Wen, Jie Min, Jiancong Wang, David Han, Jianbo Shi: "*Learning Object Placement by Inpainting for Compositional Data Augmentation*" ECCV (2020) [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580562.pdf)

+ Samaneh Azadi, Deepak Pathak, Sayna Ebrahimi, Trevor Darrell: "*Compositional GAN: Learning Image-Conditional Binary Composition*" International Journal of Computer Vision (2020) [[arXiv]](https://arxiv.org/abs/1807.07560) [[code]](https://github.com/azadis/CompositionalGAN)

+ Song-Hai Zhang, Zhengping Zhou, Bin Liu, Xi Dong, Peter Hall: "*What and Where: A Context-based Recommendation System for Object Insertion*" Computational Visual Media (2020) [[arXiv]](https://arxiv.org/abs/1811.09783)

+ Shashank Tripathi, Siddhartha Chandra, Amit Agrawal, Ambrish Tyagi, James M. Rehg, Visesh Chari: "*Learning to Generate Synthetic Data via Compositing*" CVPR (2019) [[arXiv]](https://arxiv.org/abs/1904.05475)

+ Haoshu Fang, Jianhua Sun, Runzhong Wang, Minghao Gou, Yonglu Li, Cewu Lu: "*InstaBoost: Boosting Instance Segmentation via Probability Map Guided Copy-Pasting*" ICCV (2019) [[arXiv]](https://arxiv.org/abs/1908.07801) [[code]](https://github.com/GothicAi/Instaboost)

+ Chen-Hsuan Lin, Ersin Yumer, Oliver Wang, Eli Shechtman, Simon Lucey: "*ST-GAN: Spatial Transformer Generative Adversarial Networks for Image Compositing*" CVPR (2018) [[arXiv]](https://arxiv.org/abs/1803.01837) [[code]](https://github.com/chenhsuanlin/spatial-transformer-GAN)

+ Donghoon Lee, Sifei Liu, Jinwei Gu, Ming-Yu Liu, Ming-Hsuan Yang, Jan Kautz: "*Context-Aware Synthesis and Placement of Object Instances*" NeurIPS (2018) [[arXiv]](https://arxiv.org/abs/1812.02350) [[code]](https://github.com/NVlabs/Instance_Insertion)

+ Fuwen Tan, Crispin Bernier, Benjamin Cohen, Vicente Ordonez, Connelly Barnes: "*Where and Who? Automatic Semantic-Aware Person Composition*" WACV (2018) [[arXiv]](https://arxiv.org/abs/1706.01021)[[code]](https://github.com/fwtan/who_where)

+ Tal Remez, Jonathan Huang, Matthew Brown: "*learning to segment via cut-and-paste*" ECCV (2018) [[arXiv]](https://arxiv.org/abs/1803.06414) [[code]](https://github.com/FLoosli/CP_GAN)

#### Occlusion
+ Samaneh Azadi, Deepak Pathak, Sayna Ebrahimi, Trevor Darrell: "*Compositional GAN: Learning Image-Conditional Binary Composition.*" IJCV (2020) [[arXiv]](https://arxiv.org/pdf/1807.07560.pdf) [[code]](https://github.com/azadis/CompositionalGAN)
+ Fangneng Zhan, Jiaxing Huang, Shijian Lu, "*Hierarchy Composition GAN for High-fidelity Image Synthesis.*" Transactions on cybernetics (2021) [[arXiv]](https://arxiv.org/pdf/1905.04693.pdf)

## Datasets
+ **iHarmony4:**  It contains four subdatasets: HCOCO, HAdobe5k,	HFlickr, Hday2night, with a total of 73,146 pairs of unharmonized images and harmonized images. [[link]](https://github.com/bcmi/Image_Harmonization_Datasets)
+ **GMSDataset**: It contains 183 images with image resolution of 1940*1440. It consists of 16 different objects and for each object, one source image and 11 target images in different background scenes and illumination conditions are captured. [[paper]]() [[link]](https://pan.baidu.com/s/141bLd3kjw8I4L7vUhYiEnQ) (access code: ekn2)
+ **RHHarmony**: A rendered image harmonization dataset, which contains 15000 ground-truth rendered images and has the potential to generate 135000 composite rendered images. [[link]](https://github.com/bcmi/Rendered_Image_Harmonization_Datasets)
+ **Shadow-AR:**  It contains 3,000 quintuples,  Each quintuple consists of 5 images 640×480 resolution: a synthetic image without the virtual object shadow and its corresponding image containing the virtual object shadow, a mask of the virtual object, a labeled real-world shadow matting and its corresponding labeled occluder. [[link]](https://github.com/ldq9526/ARShadowGAN)
+ **SUNCG dataset**:  It consists of 45,622 indoor scenes with over 5M 3D object instances from 37 categories. [[link]](https://sscnet.cs.princeton.edu/)
+ **Shapenet dataset**: It consists of two subsets: ShapeNetCore and ShapeNetSem. ShapeNetCore is a subset of the full ShapeNet dataset with single clean 3D models and manually verified category and alignment annotations, covering 55 common object categories with about 51,300 unique 3D models. ShapeNetSem is a smaller, more densely annotated subset consisting of 12,000 models spread over a broader set of 270 categories.[[link]](https://shapenet.org/)
+ **CelebA dataset**: It consists of 10,177 number of identities, 202,599 number of face images, and 5 landmark locations, 40 binary attributes annotations per image. [[link]](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

## Related topics

#### Video harmonization
+ Haozhi Huang, Senzhe Xu, Junxiong Cai, Wei Liu, Shimin Hu: "*Temporally Coherent Video Harmonization Using Adversarial Networks.*" IEEE Trans. Image Process. 29: 214-224 (2020) [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8765343) [[arXiv]](https://arxiv.org/abs/1809.01372)

## Other resources

+ [Awesome-ImageHarmonization](https://github.com/subeeshvasu/Awesome-ImageHarmonization)
