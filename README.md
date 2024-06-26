# Quick navigation

- [Quick navigation](#quick-navigation)
- [Awesome-Stereo-Super-Resolution (Continuously Updated)](#awesome-stereo-super-resolution-continuously-updated)
  - [Methods](#methods)
    - [2024](#2024)
    - [2023](#2023)
    - [2022](#2022)
    - [2021](#2021)
    - [2020-2018](#2020-2018)
      - [2020](#2020)
      - [2019](#2019)
      - [2018](#2018)
    - [Non-DL based SR Methods](#non-dl-based-sr-methods)
  - [Stereo Super Resolution Dataset](#stereo-super-resolution-dataset)
    - [Dataset collections](#dataset-collections)
  - [Stereo Super Resolution Competitions](#stereo-super-resolution-competitions)
<!-- - [Super Resolution survey](sr_survey.md) -->
<!-- - [Super Resolution workshop papers](workshops.md) -->

# Awesome-Stereo-Super-Resolution (Continuously Updated)

Welcome to Awesome-Stereo-Super-Resolution! This list aims to gather resources related to stereo super-resolution, including papers, datasets, and repositories. We appreciate the efforts of those who have contributed to similar lists. Let's build a comprehensive resource together!

We refer to [Awesome-Super-Resolution](https://github.com/ChaofWang/Awesome-Super-Resolution) for the navigation format for now.

**You can find other awesome paper lists and repos  from [here](awesome_paper_list_and_repos.md).**


## Methods

**You can find PSNR/SSIM results of SOTA methods on datasets, Middlebury, KITTI 2012, KITTI 2015 and Flickr1024,  from [here](psnr_ssim_results.md).**

### 2024
<!-- More years papers, plase check Quick navigation -->

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     | 
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | 
| Efficient Hybrid Feature Interaction Network for Stereo Image Super-Resolution | EHFSSR | [TMM24](https://arxiv.org/abs/2311.16518) | [code](https://github.com/jianwensong/EHFSSR) | Stereo image super-resolution, Cross-view, Intra-view, Hybrid feature interaction |


### 2023
More years papers, plase check Quick navigation

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     | 
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | 
|Toward Real World Stereo Image Super-Resolution via Hybrid Degradation Model and Discriminator for Implied Stereo Image Information        | SCGLANet            | [NTIRE2023, Expert Systems with Applications 2024](https://arxiv.org/pdf/2312.07934v1)            | [code](https://github.com/fzuzyb/SCGLANet)              | Stereo Image Super-Resolution, Real-World, Disparity, Visual Perception      | 
|SC-NAFSSR: Perceptual-Oriented Stereo Image Super-Resolution Using Stereo Consistency Guided NAFSSR        | SC-NAFSSR            | [CVPRW23 ](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Qiu_SC-NAFSSR_Perceptual-Oriented_Stereo_Image_Super-Resolution_Using_Stereo_Consistency_Guided_NAFSSR_CVPRW_2023_paper.pdf)            | [code](https://github.com/FVL2020/SC-NAFSSR)              | -      | 
| Stereo Cross Global Learnable Attention Module for Stereo Image Super-Resolution        | SCGLANet           | [CVPRW23 ](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Zhou_Stereo_Cross_Global_Learnable_Attention_Module_for_Stereo_Image_Super-Resolution_CVPRW_2023_paper.pdf)            | [code](https://github.com/fzuzyb/SCGLANet)              | -      | 
|  SwinFSR: Stereo Image Super-Resolution using SwinIR and Frequency Domain Knowledge        | SwinFSR           | [CVPRW23 ](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Chen_SwinFSR_Stereo_Image_Super-Resolution_Using_SwinIR_and_Frequency_Domain_Knowledge_CVPRW_2023_paper.pdf)            | [code](https://github.com/GoKerrChen/SwinFSR)              | [NTIRE@CVPR 2023 Stereo Image Super-Resolution Challenge](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2023)       | 
|  Steformer: Efficient Stereo Image Super-Resolution With Transformer        | Steformer           | [TMM23 ](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10016671)            | -              | Stereo image processing, image super-resolution,  transformer       | 


### 2022
More years papers, plase check Quick navigation

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |   Proposed  DataSet     |
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --- |
|NAFSSR: Stereo Image Super-Resolution Using NAFNet        | SSRDE-FNet            | [CVPRW22](https://arxiv.org/pdf/2106.00985)            | [code](https://github.com/megvii-research/NAFNet)              | -      | - |
|A New Dataset and Transformer for Stereoscopic Video Super-Resolution        | Trans-SVSR           | [CVPRW22](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Imani_A_New_Dataset_and_Transformer_for_Stereoscopic_Video_Super-Resolution_CVPRW_2022_paper.pdf)            | [code](https://github.com/H-deep/Trans-SVSR)              | -      | [SVSR-Set](https://www.shorturl.at/mpwGX) |
|SIR-Former: Stereo Image Restoration Using Transformer        | SIR-Former            | [ACM MM22 ](https://dl.acm.org/doi/pdf/10.1145/3503161.3548177)            | -              | stereo images restoration, image super-resolution, transformer      | - |
| SwiniPASSR: Swin Transformer Based Parallax Attention Network for Stereo Image Super-Resolution        | SwiniPASSR(SSR)            | [CVPR22 ](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Jin_SwiniPASSR_Swin_Transformer_Based_Parallax_Attention_Network_for_Stereo_Image_CVPRW_2022_paper.pdf)            | [code](https://github.com/Subury/NTIRE22_SSR_SwiniPASSR)              | [NTIRE@CVPR 2022 Stereo Image Super-Resolution Challenge](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2024) , **Second Place** 🥈  | - |
|SwinFIR: Revisiting the SwinIR with Fast Fourier Convolution and Improved Training for Image Super-Resolution        | SwinFIR(SSR)            | [arXiv22 ](https://arxiv.org/pdf/2208.11247)            | [code](https://github.com/Zdafeng/SwinFIR)              | The author team won [NTIRE@CVPR 2024 Stereo Image Super-Resolution Challenge](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2024) - <br> [Track 1 Constrained SR & Bicubic Degradation](https://codalab.lisn.upsaclay.fr/competitions/17245), **First Place** 🥇 <br>  [Track 2 Constrained SR & Realistic Degradation](https://codalab.lisn.upsaclay.fr/competitions/17246), **First Place** 🥇 <br> [NTIRE@CVPR 2023 Stereo Image Super-Resolution Challenge](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2023) - [Track 2 Perceptual & Bicubic](https://codalab.lisn.upsaclay.fr/competitions/10048), **First Place** 🥇     | - |



### 2021
More years papers, plase check Quick navigation

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|Feedback Network for Mutually Boosted Stereo Image Super-Resolution and Disparity Estimation        | SSRDE-FNet            | [ACM MM21](https://arxiv.org/pdf/2106.00985)            | [code](https://github.com/MIVRC/SSRDEFNet-PyTorch)              | Stereo image super-resolution, disparity estimation, mutually boosted      | -
|Perception-Oriented Stereo Image Super-Resolution        | Dateset: Mid3D_QA            | [ACM MM21](https://arxiv.org/pdf/2207.06617)            | -              | stereo image, super-resolution, quality assessment      |
|Cross Parallax Attention Network for Stereo Image Super-Resolution        | CPASSRnet            | [TMM21](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9318556)            | [code](https://github.com/canqChen/CPASSRnet)              | Stereo super-resolution, single model for multiple scaling factors, attention mechanism, convolutional neural network      | 
|Deep Bilateral Learning for Stereo Image Super-Resolution       | BSSRnet            | [SPL21](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9382858)            | [code](https://github.com/xuqingyu26/BSSRnet)      | Bilateral filter, recursive, stereo image, super-resolution     | 
|Symmetric Parallax Attention for Stereo Image Super-Resolution       | iPASSR            | [CVPRW21](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Wang_Symmetric_Parallax_Attention_for_Stereo_Image_Super-Resolution_CVPRW_2021_paper.pdf)            | [code](https://github.com/YingqianWang/iPASSR)      | -     | 
|A Disparity Feature Alignment Module for Stereo Image Super-Resolution       | DFAM module           | [SPL21](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9449947)            | [code](https://github.com/JiawangDan/DFAM)      | Super-resolution, stereo image, disparity information, attention mechanism     | 
|Cross View Capture for Stereo Image Super-Resolution       | CVCnet   | [TMM21](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9465749)            | [code](https://github.com/xyzhu1/CVCnet)      | Stereo image, super-resolution, cross view capture, spatial perception     | 
| Stereo Video Super-Resolution via Exploiting View-Temporal Correlations        | SVSRNet            | [ACM MM21](https://dl.acm.org/doi/pdf/10.1145/3474085.3475189)            | -             | Stereo video, video super-resolution, view-temporal correlations      | 
| Perception-Oriented Stereo Image Super-Resolution       | PSSR            | [ACM MM21](https://dl.acm.org/doi/pdf/10.1145/3474085.3475408)            | -             | stereo image, super-resolution, quality assessment      | 


### 2020-2018 

#### 2020

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |  
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ 
|A Stereo Attention Module for Stereo Image Super-Resolution        | SAM module (SRRes+SAM)           | [SPL20](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8998204)            | [code](https://github.com/XinyiYing/SAM)              |    Attention mechanism, stereo vision, super resolution    | 
|Stereoscopic image super-resolution with stereo consistent feature        | SPAM module           | [AAAI20](https://ojs.aaai.org/index.php/AAAI/article/view/6880)            | -             | -   | 
|Disparity-Aware Domain Adaptation in Stereo Image Restoration        | DASSR           | [CVPR20](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yan_Disparity-Aware_Domain_Adaptation_in_Stereo_Image_Restoration_CVPR_2020_paper.pdf)            | -              |    -    | 
|Deep Stereoscopic Image Super-Resolution via Interaction Module        | IMSSRnet           | [TCSVT20](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9253563)            | -              |   Terms-Super-resolution, stereoscopic image, interaction module, deep learning  |   

#### 2019

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     | 
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | 
|Dual-Stream Interactive Networks for No-Reference Stereoscopic Image Quality Assessment        |  StereoQA-Net            | [TIP19](https://www.researchgate.net/profile/Wei-Zhou-53/publication/331537376_Dual-Stream_Interactive_Networks_for_No-Reference_Stereoscopic_Image_Quality_Assessment/links/5c80cb8b299bf1268d4077cb/Dual-Stream-Interactive-Networks-for-No-Reference-Stereoscopic-Image-Quality-Assessment.pdf)            | -            | Stereoscopic image quality assessment, dual-stream, interactive network, human vision, end-to-end prediction      | 
|Learning Parallax Attention for Stereo Image Super-Resolution        |  PASSRnet            | [CVPR19](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Learning_Parallax_Attention_for_Stereo_Image_Super-Resolution_CVPR_2019_paper.pdf)            | [code](https://github.com/The-Learning-And-Vision-Atelier-LAVA/PASSRnet)            | Stereoscopic image quality assessment, dual-stream, interactive network, human vision, end-to-end prediction      | 

#### 2018

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |   
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | 
|Enhancing the Spatial Resolution of Stereo Images using a Parallax Prior   |    StereoSR     | [CVPR18](https://openaccess.thecvf.com/content_cvpr_2018/papers/Jeon_Enhancing_the_Spatial_CVPR_2018_paper.pdf)            | [code](https://github.com/PeterZhouSZ/stereosr)              | -      | 

### Non-DL based SR Methods

This part is mainly referenced from [Awesome-Super-Resolution](https://github.com/ChaofWang/Awesome-Super-Resolution).

| Title                  | Model                  | Published                                                    | Code                                                         | Keywords                                                     |   
| ---------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | 
| Image Super-Resolution Via Sparse Representation   |    SCSR     | [TIP2010](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5466111)            | [code](http://www.ifp.illinois.edu/~jyang29/)              | Face hallucination, image super-resolution (SR), nonnegative matrix factorization, sparse coding, sparse representation      | 
| Anchored Neighborhood Regression for Fast Example-Based Super-Resolution   |    ANR     | [ICCV2013](https://openaccess.thecvf.com/content_iccv_2013/papers/Timofte_Anchored_Neighborhood_Regression_2013_ICCV_paper.pdf)            | [code](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)              | -      | 
| A+: Adjusted Anchored Neighborhood Regression for Fast Super-Resolution   |    A+     | [ACCV2014](https://ieeexplore.ieee.org/document/5466111/?arnumber=5466111)            | [code](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)              | -      | 
| Seven ways to improve example-based single image super resolution   |    IA     | [CVPR2016](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Timofte_Seven_Ways_to_CVPR_2016_paper.pdf)            | -              | -     | 
| Single Image Super-resolution from Transformed Self-Exemplars |    SelfExSR     | [CVPR2015](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Huang_Single_Image_Super-Resolution_2015_CVPR_paper.pdf)            | [code](https://github.com/jbhuang0604/SelfExSR)              | -      | 
| Naive Bayes Super-Resolution Forest   |    NBSRF     | [ICCV2015](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Salvador_Naive_Bayes_Super-Resolution_ICCV_2015_paper.pdf)            |    -     | -      | 
| Fast and Accurate Image Upscaling with Super-Resolution Forests  |    SCSR     | [ICCV2015](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Schulter_Fast_and_Accurate_2015_CVPR_paper.pdf)            | [code](https://www.tugraz.at/institute/icg/research/team-bischof/samuel-schulter/)              | -      | 

## Stereo Super Resolution Dataset


|     Name     |   Usage    |                             Link                             |                        Comments                        |
| :----------: | :--------: | :----------------------------------------------------------: | :----------------------------------------------------: |
|  **Flick1024**     | Train/Test |     [website](https://yingqianwang.github.io/Flickr1024/)     |                       a large-scale stereo image dataset which consists of 1024 high-quality image pairs and covers diverse senarios    , [ICCVW19](https://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Wang_Flickr1024_A_Large-Scale_Dataset_for_Stereo_Image_Super-Resolution_ICCVW_2019_paper.pdf)                    |
|  **KITTI 2012**     | Train/Test |     [website](https://www.cvlibs.net/datasets/kitti/eval_stereo_flow.php?benchmark=stereo)     |         The stereo / flow benchmark consists of 194 training image pairs and 195 test image pairs, saved in loss less png format, [CVPR12](https://projet.liris.cnrs.fr/imagine/pub/proceedings/CVPR2012/data/papers/424_O3C-04.pdf)                   |
|  **KITTI 2015**     | Train/Test |     [website](https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo)     |  The stereo 2015 / flow 2015 / scene flow 2015 benchmark consists of 200 training scenes and 200 test scenes (4 color images per scene, saved in loss less png format), [CVPR15](https://openaccess.thecvf.com/content_cvpr_2015/papers/Menze_Object_Scene_Flow_2015_CVPR_paper.pdf), [CVPR16](https://openaccess.thecvf.com/content_cvpr_2016/papers/Mayer_A_Large_Dataset_CVPR_2016_paper.pdf)                   |
|  **Middlebury**     | Train/Test |     [website](https://vision.middlebury.edu/stereo/data/)     |                       High-resolution stereo datasets with subpixel-accurate ground truth,    [GCPR14](https://www.cs.middlebury.edu/~schar/papers/datasets-gcpr2014.pdf)                   |

<!-- 
### Single Image Super Resolution Dataset

BSDS

DIV2K

Flickr2K -->

### Dataset collections
SSR **testing** datasets collected by [iPASSR](https://github.com/YingqianWang/iPASSR): Flickr1024, KITTI2012, KITTI2015, Middlebury including bicubic downsamples with x2, x4
[Google Dirve](https://drive.google.com/file/d/1LQDUclNtNZWTT41NndISLGvjvuBbxeUs/view?usp=sharing), [Baidu Drive](https://pan.baidu.com/s/1SIYGcMBEDDZ0wYrkxL9bnQ) (Key: NUDT)

SSR **training** datasets collected by [iPASSR](https://github.com/YingqianWang/iPASSR): Flickr1024, Middlebury
[Baidu Drive](https://pan.baidu.com/s/173UGmmN0rtOUghIT40oy8w) (Key: NUDT)

## Stereo Super Resolution Competitions

| Name | Link | Results | Conference |
| ---- | ---- | ------- | ---------- |
| **NTIRE 2024 Challenge on Stereo Image Super-Resolution** | [Github](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2024) | Results | CVPR24 |
| **NTIRE 2023 Challenge on Stereo Image Super-Resolution** | [Github](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2023) | [Results](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Wang_NTIRE_2023_Challenge_on_Stereo_Image_Super-Resolution_Methods_and_Results_CVPRW_2023_paper.pdf)| CVPR23 |
| **NTIRE 2022 Challenge on Stereo Image Super-Resolution** | [Github](https://github.com/The-Learning-And-Vision-Atelier-LAVA/Stereo-Image-SR/tree/NTIRE2022) | [Results](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Wang_NTIRE_2022_Challenge_on_Stereo_Image_Super-Resolution_Methods_and_Results_CVPRW_2022_paper.pdf)| CVPR22 |