
### PSNR/SSIM results of SOTA methods


#### PSNR/SSIM results on *KITTI 2012 2x*

| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 28.44/0.8808 | 28.51/0.8842 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 30.17/0.9062 | 30.30/0.9089 | 2016 |
| EDSR | 38.6M | [DIV2K](dataset.md) | 30.83/0.9199 | 30.96/0.9228 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 30.81/0.9197 | 30.94/0.9227 | 2018 |
| RCAN | 15.3M | [DIV2K](dataset.md) | 30.88/0.9202 | 31.02/0.9232 | 2018 |
| StereoSR | 1.08M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 29.42/0.9040 | 29.51/0.9073 | 2018 |
| PASSRnet | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.68/0.9159 | 30.81/0.9190 | 2019 |
| IMSSRnet | 6.84M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.90/- | 30.92/- | 2020 |
| iPASSR | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.97/0.9210  | 31.11/0.9240  | 2021 |
| SSRDE-FNet  | 2.10M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.08/0.9224 | 31.23/0.9254 | 2021 |
| SIR-Former | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  31.02/0.9217  |  31.16/0.9247 | 2022 |
| NAFSSR-T | 0.45M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.12/0.9224 | 31.26/0.9254 | 2022 |
| NAFSSR-S | 1.54M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.23/0.9236 | 31.38/0.9266 | 2022 |
| NAFSSR-B | 6.77M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.40/0.9254 | 31.55/0.9283 | 2022 |
| NAFSSR-L | 23.79M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.45/0.9261 | 31.60/0.9291  | 2022 |
| SwinFIRSSR | 23.94M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | **31.65/0.9293** | **31.79/0.9321** | 2022 |
| MESFINET | 2.00M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  31.08/0.9223 |   31.22/0.9253 | 2023 |
| Steformer | 1.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 31.16/0.9236 | 31.29/0.9263 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   30.16/0.9187 | 30.96/0.9306 | 2023 |
| CVHSSR-T |  0.66M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |   31.31/0.9250 |  31.46/0.9280 | 2023 |
| CVHSSR-S | 2.22M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |  31.42/0.9262 |    31.57/0.9291 | 2023 |
|  EHFSSR-S  | 0.63M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     31.46/0.9279 | 2024 |
|  EHFSSR | 1.19M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |  31.58/0.9296 | 2024 |
| SCGLANet |  25.43M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    <u>31.61/0.9294</u>  |  <u>31.71/0.9307</u> | 2024 |

#### PSNR/SSIM results on *KITTI 2015 2x*
| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 27.81/0.8814 | 28.61/0.8973 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 28.99/0.9038 | 29.78/0.9150 | 2016 |
| EDSR | 38.6M | [DIV2K](dataset.md) | 29.94/0.9231 | 30.73/0.9335 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 29.91/0.9224 | 30.70/0.9330 | 2018 |
| RCAN | 15.3M | [DIV2K](dataset.md) | 29.97/0.9231 | 30.77/0.9336 | 2018 |
| StereoSR | 1.08M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 28.53/0.9038 | 29.33/0.9168 | 2018 |
| PASSRnet | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.81/0.9191  | 30.60/0.9300 | 2019 |
| IMSSRnet | 6.84M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.97/- | 30.66/- | 2020 |
| iPASSR | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.01/0.9234  | 30.81/0.9340  | 2021 |
| SSRDE-FNet  | 2.10M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.10/0.9245 | 30.90/0.9352 | 2021 |
| SIR-Former | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  30.11/0.9246  |  30.93/0.9355 | 2022 |
| NAFSSR-T | 0.45M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.19/0.9253 | 30.99/0.9355 | 2022 |
| NAFSSR-S | 1.54M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.28/0.9266 | 31.08/0.9367  | 2022 |
| NAFSSR-B | 6.77M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.42/0.9282 | 31.22/0.9380 | 2022 |
| NAFSSR-L | 23.79M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.46/0.9289 | 31.25/0.9386 | 2022 |
| SwinFIRSSR | 23.94M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | <u>30.66/0.9321</u> | **31.45/0.9413**  | 2022 |
| MESFINET | 2.00M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  30.12/0.9252 |   30.92/0.9354 | 2023 |
| Steformer | 1.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.27/0.9271 | 31.07/0.9371 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   30.16/0.9187 | 30.96/0.9306 | 2023 |
| CVHSSR-T |  0.66M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |   30.33/0.9277 |  31.13/0.9377 | 2023 |
| CVHSSR-S | 2.22M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) | 30.42/0.9287 |   31.22/0.9385 | 2023 |
|  EHFSSR-S  | 0.63M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     31.13/0.9377 | 2024 |
|  EHFSSR | 1.19M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |   31.21/0.9390 | 2024 |
| SCGLANet |  25.43M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    **31.23/0.9385**  |  <u>31.32/0.9397</u> | 2024 |

#### PSNR/SSIM results on *Middlebury 2x*
| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 30.46/0.8979 | 30.60/0.8990 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 32.66/0.9101 | 32.77/0.9102 | 2016 |
| EDSR | 38.6M | [DIV2K](dataset.md) | 34.84/0.9489 | 34.95/0.9492 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 34.85/0.9488 | 34.94/0.9491 | 2018 |
| RCAN | 15.3M | [DIV2K](dataset.md) | 34.80/0.9482 | 34.90/0.9486 | 2018 |
| StereoSR | 1.08M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 33.15/0.9343 | 33.23/0.9348 | 2018 |
| PASSRnet | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 34.13/0.9421 | 34.23/0.9422 | 2019 |
| IMSSRnet | 6.84M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 34.66/- | 34.67/- | 2020 |
| iPASSR | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 34.41/0.9454 | 34.51/0.9454 | 2021 |
| SSRDE-FNet  | 2.10M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 35.02/0.9508  | 35.09/0.9511 | 2021 |
| SIR-Former | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  34.87/0.9490  |  34.95/0.9495 | 2022 |
| NAFSSR-T | 0.45M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 34.93/0.9495  | 35.01/0.9495 | 2022 |
| NAFSSR-S | 1.54M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 35.23/0.9515 | 35.30/0.9514 | 2022 |
| NAFSSR-B | 6.77M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 35.62/0.9545 | 35.68/0.9544 | 2022 |
| NAFSSR-L | 23.79M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 35.83/0.9559 | 35.88/0.9557 | 2022 |
| SwinFIRSSR | 23.94M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | **36.48/0.9601** | **36.52/0.9598** | 2022 |
| MESFINET | 2.00M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  35.15/0.9511 |   35.21/0.9510 | 2023 |
| Steformer | 1.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 35.15/0.9512 | 35.23/0.9511 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  35.08/0.9516 | 35.21/0.9520 | 2023 |
| CVHSSR-T |  0.66M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |  35.41/0.9533 |  35.47/0.9532 | 2023 |
| CVHSSR-S | 2.22M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) | 35.73/0.9551 |  35.78/0.9550 | 2023 |
|  EHFSSR-S  | 0.63M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     35.51/0.9530 | 2024 |
|  EHFSSR | 1.19M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |   35.71/0.9545 | 2024 |
| SCGLANet |  25.43M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    <u>36.26/0.9587</u>  |  <u>36.33/0.9583</u> | 2024 |

#### PSNR/SSIM results on *Flickr1024 2x*
| Method | Parameters | Training Dataset | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|
| Bicubic | - | - | 24.94/0.8186 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 25.60/0.8534 | 2016 |
| EDSR | 38.6M | [DIV2K](dataset.md) | 28.66/0.9087 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 28.64/0.9084 | 2018 |
| RCAN | 15.3M | [DIV2K](dataset.md) | 28.63/0.9082 | 2018 |
| StereoSR | 1.08M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 25.96/0.8599 | 2018 |
| PASSRnet | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.38/0.9038 | 2019 |
| iPASSR | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.60/0.9097 | 2021 |
| SSRDE-FNet  | 2.10M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.85/0.9132 | 2021 |
| SIR-Former | 1.37M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   28.69/0.9103 | 2022 |
| NAFSSR-T | 0.45M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.94/0.9128 | 2022 |
| NAFSSR-S | 1.54M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.19/0.9160 | 2022 |
| NAFSSR-B | 6.77M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.54/0.9204 | 2022 |
| NAFSSR-L | 23.79M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.68/0.9221 | 2022 |
| SwinFIRSSR | 23.94M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | **30.14/0.9286** | 2022 |
| MESFINET | 2.00M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    28.97/0.9145 | 2023 |
| Steformer | 1.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.97/0.9141 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  29.05/0.9049 | 2023 |
| CVHSSR-T |   0.66M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) | 29.26/0.9180 | 2023 |
| CVHSSR-S |  2.22M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |  29.56/0.9216 | 2023 |
|  EHFSSR-S  | 0.63M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |       29.31/0.9182 | 2024 |
|  EHFSSR | 1.19M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   29.51/0.9210 | 2024 |
| SCGLANet |  25.43M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    <u>29.97/0.9257</u> | 2024 |


<!-- | IMSSRnet | 6.84M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | -/- | 2020 | -->

#### PSNR/SSIM results on *KITTI 2012 4x*
| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 24.52/0.7310 | 24.58/0.7372 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 25.54/0.7662 | 25.60/0.7722 | 2016 |
| EDSR | 38.9M | [DIV2K](dataset.md) | 26.26/0.7954  | 26.35/0.8015 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 26.23/0.7952 | 26.32/0.8014 | 2018 |
| RCAN | 15.4M | [DIV2K](dataset.md) | 26.36/0.7968 | 26.44/0.8029  | 2018 |
| StereoSR | 1.42M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 24.49/0.7502 | 24.53/0.7555 | 2018 |
| PASSRnet | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.26/0.7919 | 26.34/0.7981 | 2019 |
| SRRes+SAM | 1.73M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.35/0.7957 | 26.44/0.8018  | 2021 |
| IMSSRnet | 6.89M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.44/- | 26.43/- | 2020 | 28.66/0.9087 |
| iPASSR | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.47/0.7993 | 26.56/0.8053 | 2021 |
| SSRDE-FNet  | 2.24M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.61/0.8028 | 26.70/0.8082 | 2021 |
| SIR-Former | 1.48M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  26.53/0.7998  |   26.68/0.8077 | 2022 |
| NAFSSR-T | 0.46M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.69/0.8045 | 26.79/0.8105 | 2022 |
| NAFSSR-S | 1.56M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.84/0.8086 | 26.93/0.8145 | 2022 |
| NAFSSR-B | 6.80M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.99/0.8121 | 27.08/0.8181 | 2022 |
| NAFSSR-L | 23.83M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 27.04/0.8135 | 27.12/0.8194 | 2022 |
| SwinFIRSSR | 24.09M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 27.06/0.8175 | 27.16/0.8235 | 2022 |
| SwinFSR-S | 9.76M | [Flickr1024](dataset.md) | - | 27.03/0.8143  | 2023 |
| SwinFSR-B | 14.01M | [Flickr1024](dataset.md) | - | 27.07/0.8151  | 2023 |
| SwinFSR-L | 26.75M | [Flickr1024](dataset.md) | - | <u>27.24/0.8195</u> | 2023 |
| MESFINET | 2.05M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  26.61/0.8039 |   26.70/0.8099 | 2023 |
| HTCAN | 25.29M |  [Flickr1024](dataset.md) |   **27.16/0.8189** |   **27.25/0.8249** | 2023 |
| Steformer | 1.34M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.61/0.8037 | 26.70/0.8098 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    26.64/0.7913 |  26.77/0.7998 | 2023 |
| CVHSSR-T |  0.68M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |    26.88/0.8105 |  26.98/0.8165  | 2023 |
| CVHSSR-S | 2.24M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |  27.00/0.8139 |     27.10/0.8199 | 2023 |
|  EHFSSR-S  | 0.64M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     26.79/0.8218 | 2024 |
|  EHFSSR | 1.21M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |   26.82/0.8233 | 2024 |
| SCGLANet | 25.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    <u>27.10/0.8204</u>  |  27.20/0.8230 | 2024 |


#### PSNR/SSIM results on *KITTI 2015 4x*
| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 23.79/0.7072 | 24.38/0.7340 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 24.68/0.7456  | 25.32/0.7703 | 2016 |
| EDSR | 38.9M | [DIV2K](dataset.md) | 25.38/0.7811  | 26.04/0.8039 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 25.37/0.7813 | 26.04/0.8043  | 2018 |
| RCAN | 15.4M | [DIV2K](dataset.md) | 25.53/0.7836 | 26.22/0.8068  | 2018 |
| StereoSR | 1.42M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 23.67/0.7273 | 24.21/0.7511 | 2018 |
| PASSRnet | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.41/0.7772 | 26.08/0.8002  | 2019 |
| SRRes+SAM | 1.73M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.55/0.7825 | 26.22/0.8054  | 2021 |
| IMSSRnet | 6.89M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.59/- | 26.20/- | 2020 | 28.66/0.9087 |
| iPASSR | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.61/0.7850  | 26.32/0.8084 | 2021 |
| SSRDE-FNet  | 2.24M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.74/0.7884  | 26.43/0.8118 | 2021 |
| SIR-Former | 1.48M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  25.75/0.7882 |   26.42/0.8098 | 2022 |
| NAFSSR-T | 0.46M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.90/0.7930 | 26.62/0.8159 | 2022 |
| NAFSSR-S | 1.56M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.03/0.7978  | 26.76/0.8203 | 2022 |
| NAFSSR-B | 6.80M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.17/0.8020 | 26.91/0.8245 | 2022 |
| NAFSSR-L | 23.83M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.22/0.8034 | 26.96/0.8257  | 2022 |
| SwinFIRSSR | 24.09M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 26.15/0.8062 | 26.89/0.8283 | 2022 |
| SwinFSR-S | 9.76M | [Flickr1024](dataset.md) | - | 26.83/0.8213  | 2023 |
| SwinFSR-B | 14.01M | [Flickr1024](dataset.md) | - | 26.87/0.8222 | 2023 |
| SwinFSR-L | 26.75M | [Flickr1024](dataset.md) | - | <u>27.00/0.8257</u> | 2023 |
| MESFINET | 2.05M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  25.69/0.7897 |   26.42/0.8131 | 2023 |
| Steformer | 1.34M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 25.74/0.7906 | 26.45/0.8134 | 2023 |
| HTCAN | 25.29M |  [Flickr1024](dataset.md) |  <u>26.26/0.8083</u> |   26.99/0.8299 | 2023 |
| SC-NAFSSR | - |  [Flickr1024](dataset.md) |  - |   24.89/0.7582 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    25.76/0.7775 |  26.54/0.8083 | 2023 |
| CVHSSR-T |  0.68M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |    26.03/0.7991 |  26.78/0.8218  | 2023 |
| CVHSSR-S | 2.24M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |  26.15/0.8033 |     26.90/0.8258 | 2023 |
|  EHFSSR-S  | 0.64M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     26.79/0.8218 | 2024 |
|  EHFSSR | 1.21M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |   26.82/0.8233 | 2024 |
| SCGLANet | 25.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   **26.94/0.8268**  | **27.01/0.8290** | 2024 |

#### PSNR/SSIM results on *Middlebury 4x*
| Method | Parameters | Training Dataset | *Left* | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|-|
| Bicubic | - | - | 26.27/0.7553 | 26.40/0.7572 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 27.60/0.7933  | 27.69/0.7941 | 2016 |
| EDSR | 38.9M | [DIV2K](dataset.md) | 29.15/0.8383  | 29.23/0.8397 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 29.15/0.8387  | 29.27/0.8404 | 2018 |
| RCAN | 15.4M | [DIV2K](dataset.md) | 29.20/0.8381 | 29.30/0.8397  | 2018 |
| StereoSR | 1.42M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 27.70/0.8036 | 27.64/0.8022 | 2018 |
| PASSRnet | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.61/0.8232  | 28.72/0.8236 | 2019 |
| SRRes+SAM | 1.73M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 28.76/0.8287  | 28.83/0.8290  | 2021 |
| IMSSRnet | 6.89M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.02/-  | 29.02/-  | 2020 | 28.66/0.9087 |
| iPASSR | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.07/0.8363  | 29.16/0.8367  | 2021 |
| SSRDE-FNet  | 2.24M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.29/0.8407 | 29.38/0.8411 | 2021 |
| SIR-Former | 1.48M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  29.23/0.8396 |   29.32/0.8407 | 2022 |
| NAFSSR-T | 0.46M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.22/0.8403 | 29.32/0.8409 | 2022 |
| NAFSSR-S | 1.56M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.62/0.8482 | 29.72/0.8490 | 2022 |
| NAFSSR-B | 6.80M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.94/0.8561 | 30.04/0.8568  | 2022 |
| NAFSSR-L | 23.83M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 30.11/0.8601 | 30.20/0.8605 | 2022 |
| SwinFIRSSR | 24.09M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | **30.33/0.8676** | 30.44/0.8687 | 2022 |
| SwinFSR-S | 9.76M | [Flickr1024](dataset.md) | - | 32.45/0.8891 | 2023 |
| SwinFSR-B | 14.01M | [Flickr1024](dataset.md) | - | <u>32.69/0.8910</u> | 2023 |
| SwinFSR-L | 26.75M | [Flickr1024](dataset.md) | - | **32.73/0.8915** | 2023 |
| MESFINET | 2.05M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  29.32/0.8434 |   29.42/0.8438 | 2023 |
| Steformer | 1.34M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 29.29/0.8424 | 29.38/0.8425 | 2023 |
| HTCAN | 25.29M |  [Flickr1024](dataset.md) |   <u>30.25/0.8628</u> |  30.33/0.8634 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |     29.58/0.8418 |  29.74/0.8426 | 2023 |
| CVHSSR-T |  0.68M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |    29.62/0.8496 |  29.74/0.8505  | 2023 |
| CVHSSR-S | 2.24M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |   29.94/0.8577 |    30.05/0.8584 | 2023 |
|  EHFSSR-S  | 0.64M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  - |     29.79/0.8506 | 2024 |
|  EHFSSR | 1.21M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |  -  |   29.87/0.8540 | 2024 |
| SCGLANet | 25.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |   30.23/0.8628  |    30.38/0.8642 | 2024 |

#### PSNR/SSIM results on *Flickr1024 4x*
| Method | Parameters | Training Dataset | *(Left+Right)/2* | Published Year |
|-|-|-|-|-|
| Bicubic | - | - | 21.82/0.6293 | - |
| VDSR | 0.66M | 200 BSDS, 91 images from [Yang et al.](https://ieeexplore.ieee.org/abstract/document/5466111) | 22.46/0.6718 | 2016 |
| EDSR | 38.9M | [DIV2K](dataset.md) | 23.46/0.7285 | 2017 |
| RDN | 22.0M | [DIV2K](dataset.md) | 23.47/0.7295 | 2018 |
| RCAN | 15.4M | [DIV2K](dataset.md) | 23.48/0.7286 | 2018 |
| StereoSR | 1.42M | 60 [Middlebury](dataset.md), [KITTI 2012/2015](dataset.md), Tsukuba | 21.70/0.6460 | 2018 |
| PASSRnet | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.31/0.7195 | 2019 |
| SRRes+SAM | 1.73M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.27/0.7233 | 2021 |
| iPASSR | 1.42M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.44/0.7287 | 2021 |
| SSRDE-FNet  | 2.24M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.59/0.7352 | 2021 |
| SIR-Former | 1.48M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |     23.52/0.7305 | 2022 |
| NAFSSR-T | 0.46M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.69/0.7384 | 2022 |
| NAFSSR-S | 1.56M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.88/0.7468 | 2022 |
| NAFSSR-B | 6.80M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 24.07/0.7551 | 2022 |
| NAFSSR-L | 23.83M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 24.17/0.7589 | 2022 |
| SwinFIRSSR | 24.09M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | <u>24.29/0.7681</u>  | 2022 |
| SwiniPASSR-S2 | 16.55M | [Flickr1024](dataset.md) | 24.00/0.7549 | 2023 |
| SwiniPASSR-M2 | 22.81M | [Flickr1024](dataset.md) | 24.05/0.7560 | 2023 |
| SwiniPASSR-M2 <br> ***using self-ensemble strategy*** | 22.81M | [Flickr1024](dataset.md) | 24.13/0.7579 | 2023 |
| SwinFSR-S | 9.76M | [Flickr1024](dataset.md) | 23.83/0.7471 | 2023 |
| SwinFSR-B | 14.01M | [Flickr1024](dataset.md) | 23.96/0.7510 | 2023 |
| SwinFSR-L | 26.75M | [Flickr1024](dataset.md) | 24.19/0.7598 | 2023 |
| MESFINET | 2.05M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |     23.63/0.7389 | 2023 |
| Steformer | 1.34M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.58/0.7376 | 2023 |
| HTCAN | 25.29M |  [Flickr1024](dataset.md) |     24.44/0.7703 | 2023 |
| SC-NAFSSR | - |  [Flickr1024](dataset.md) |     22.44/0.6918 | 2023 |
| PFT-SSR | - | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | 23.89/0.7277 | 2023 |
| CVHSSR-T |  0.68M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |   23.89/0.7484  | 2023 |
| CVHSSR-S | 2.24M | 60 [Middlebury](dataset.md)?, [Flickr1024](dataset.md) |    24.08/0.7570 | 2023 |
|  EHFSSR-S  | 0.64M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    23.92/0.7483 | 2024 |
|  EHFSSR | 1.21M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |    23.99/0.7525 | 2024 |
| SCGLANet | 25.29M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) |     **24.39/0.7679** | 2024 |

   
<!-- | IMSSRnet | 6.89M | 60 [Middlebury](dataset.md), [Flickr1024](dataset.md) | -/-  |  2020 | 28.66/0.9087 | -->
