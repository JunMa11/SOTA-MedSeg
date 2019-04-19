# State-of-the-art medical image segmentation methods based on various challenges! (Updated 201904)

## Contents
**Brain**

- 2018 MICCAI: Multimodal Brain Tumor Segmentation Challenge
- 2018 MICCAI: Ischemic stroke lesion segmentation
- 2018 MICCAI Grand Challenge on MR Brain Image Segmentation

**Chest & Abdomen**

- 2019 MICCAI: Left Ventricle Full Quantification Challenge [(Ongoing!!!)](https://github.com/TiancongHua/Left-Ventricle-Full-Quantification-Challenge-MICCAI-2019)
- 2019 MICCAI: Multi-sequence Cardiac MR Segmentation Challenge [(Ongoing!!!)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mscmrseg19/)
- 2018 MICCAI: Left Ventricle Full Quantification Challenge 
- 2018 MICCAI: Atrial Segmentation Challenge
- 2019 MICCAI: Liver Cancer Segmentation in whole-slide images (WSIs). [(Ongoing!!!)](https://paip2019.grand-challenge.org/Home/)
- 2019 MICCAI: Kidney Tumor Segmentation Challenge [(Ongoing!!!)](https://kits19.grand-challenge.org/)
- 2019 ISBI: Segmentation of THoracic Organs at Risk in CT images
- 2017 ISBI & MICCAI: Liver tumor segmentation challenge 
- 2012 MICCAI: Prostate MR Image Segmentation 

**Others**

- 2018 MICCAI Medical Segmentation Decathlon
Awesome Open Source Tools
- Loss functions for Imbalanced Problems





## Brain
### 2018 MICCAI: Multimodal Brain Tumor Segmentation Challenge[(BraTS)](https://www.med.upenn.edu/sbia/brats2018.html)
*Summary: Identifying the Best Machine Learning Algorithms for Brain Tumor Segmentation, Progression Assessment, and Overall Survival Prediction in the BRATS Challenge Spyridon Bakas et al. 201811, [(arxiv)](https://arxiv.org/abs/1811.02629)*

|Rank |First Author |Title|Val. WT/EN/TC Dice|Test Val. WT/ET/TC Dice|
|---|---|---|---|---|
|1|Andriy Myronenko|3D MRI Brain Tumor Segmentation Using Autoencoder Regularization [(paper)](https://arxiv.org/pdf/1810.11654.pdf)|0.91/0.823/0.867|0.884/0.766/0.815|
|2|[Fabian Isensee](https://scholar.google.ca/citations?user=PjerEe4AAAAJ&hl=zh-CN&oi=ao)|No New-Net [(paper)](https://arxiv.org/abs/1809.10483)|0.913/0.809/0.863|0.878/0.779/0.806|
|3|[Richard McKinley](https://scholar.google.ca/citations?user=MVFfMZcAAAAJ&hl=zh-CN&oi=sra)|Ensembles of Densely-Connected CNNs with Label-Uncertainty for Brain Tumor Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-11726-9_40)|0.903/0.796/0.847|0.732/0.886/0.799|
|3|Chenhong Zhou|Learning Contextual and Attentive Information for Brain Tumor Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-11726-9_44)|0.8136/0.9095/0.8651|0.8842/0.7775/0.7960|

### 2018 MICCAI: Ischemic stroke lesion segmentation [(ISLES )](http://www.isles-challenge.org/)

|Date |First Author |Title|Dice|
|---|---|---|---|
|201812|[Hoel Kervadec](https://scholar.google.ca/citations?user=yeFGhfgAAAAJ&hl=zh-CN&oi=sra)|Boundary loss for highly unbalanced segmentation [(paper)](https://arxiv.org/abs/1812.07032), [(pytorch 1.0 code)](https://github.com/LIVIAETS/surface-loss)|65.6|
|201809|Tao Song|3D Multi-scale U-Net with Atrous Convolution for Ischemic Stroke Lesion Segmentation, [(paper)](http://www.isles-challenge.org/articles/Tao_Song.pdf)|55.86|
|201809|Pengbo Liu|Stroke Lesion Segmentation with 2D Convolutional Neutral Network and Novel Loss Function, [(paper)](http://www.isles-challenge.org/articles/Liu_Pengbo.pdf)|55.23|
|201809|Yu Chen|Ensembles of Modalities Fused Model for Ischemic Stroke Lesion Segmentation, [(paper)](http://www.isles-challenge.org/articles/Yu_Chen.pdf)|-|

### 2018 MICCAI Grand Challenge on MR Brain Image Segmentation [(MRBrainS18)](https://mrbrains18.isi.uu.nl/)

- Eight Label Segmentation Results (201809)

|Rank |First Author |Title|Score|
|---|---|---|---|
|1|Miguel Luna|3D Patchwise U-Net with Transition Layers for MR Brain Segmentation [(paper)](https://mrbrains18.isi.uu.nl/results/eight-label-segmentation-results/mispl-2/)|9.971|
|2|Alireza Mehrtash|U-Net with various input combinations [(paper)](https://mrbrains18.isi.uu.nl/results/eight-label-segmentation-results/k2-2/)|9.915|
|3|Xuhua Ren|Ensembles of Multiple Scales, Losses and Models for Segmentation of Brain Area [(paper)](https://mrbrains18.isi.uu.nl/results/eight-label-segmentation-results/xuhuaren-2/)|9.872|

- Three Label Segmentation Results (201809)

|Rank |First Author |Title|GM/WM/CSF Dice|Score|
|---|---|---|---|---|
|1|Liyan Sun|Brain Tissue Segmentation Using 3D FCN with Multi-modality Spatial Attention [(paper)](https://mrbrains18.isi.uu.nl/results/three-label-segmentation-results/smartdsp-2/)|0.86/0.889/0.850|11.272|

## Heart
### 2019 MICCAI: Left Ventricle Full Quantification Challenge [(LVQuan19)](https://github.com/TiancongHua/Left-Ventricle-Full-Quantification-Challenge-MICCAI-2019)
**Ongoing!!! Deadline: July 3rd, 2019**
> The aim of this challenge is to learn effective machine learning models that can estimate a set of clinical significant LV indices (regional wall thicknesses, cavity dimensions, area of cavity and myocardium, cardiac phase) directly from MR images. No intermediate segmentation is required in the whole procedure.

### 2019 MICCAI: Multi-sequence Cardiac MR Segmentation Challenge [(MS-CMRSeg)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mscmrseg19/)
**Ongoing!!! Deadline: June 12th, 2019**
> Multi-sequence ventricle and myocardium segmentation.

### 2018 MICCAI: Left Ventricle Full Quantification Challenge [(LVQuan18)](https://lvquan18.github.io/)

|Rank |First Author |Title|
|---|---|---|
|1|Jiahui Li|Left Ventricle Full Quantification Using Deep Layer Aggregation Based Multitask Relationship Learning, [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-12029-0_41)|
|2|[Eric Kerfoot](https://scholar.google.ca/citations?user=AhhlyboAAAAJ&hl=zh-CN&oi=sra)|Left-Ventricle Quantification Using Residual U-Net, [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-12029-0_40)||
|3|[Fumin Guo](https://scholar.google.ca/citations?user=l49sPKYAAAAJ&hl=zh-CN&oi=sra)|Cardiac MRI Left Ventricle Segmentation and Quantification: A Framework Combining U-Net and Continuous Max-Flow [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-12029-0_6)|


## 2018 MICCAI: Atrial Segmentation Challenge [(AtriaSeg)](http://atriaseg2018.cardiacatlas.org/)

|Rank |First Author |Title|Score|
|---|---|---|---|
|1 |Qing Xia|Automatic 3D Atrial Segmentation from GE-MRIs Using Volumetric Fully Convolutional Networks [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-12029-0_23)|0.932|
|2 |Cheng Bian|Pyramid Network with Online Hard Example Mining for Accurate Left Atrium Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-12029-0_26)|0.926|
|2 |[Sulaiman Vesal](https://scholar.google.ca/citations?user=SQOL8eYAAAAJ&hl=en&oi=sra)|Dilated Convolutions in Neural Networks for Left Atrial Segmentation in 3D Gadolinium Enhanced-MR [(paper)](https://www5.informatik.uni-erlangen.de/Forschung/Publikationen/2018/Vesal18-DCI.pdf)|0.926|

## Chest and Abdomen
### 2019 MICCAI: Kidney Tumor Segmentation Challenge [(KiTS19)](https://kits19.grand-challenge.org/)
**Ongoing!!! Deadline: July 29th, 2019**
> The goal of this challenge is to accelerate the development of reliable kidney and kidney tumor semantic segmentation methodologies. We have produced ground truth semantic segmentations for arterial phase abdominal CT scans of 300 unique kidney cancer patients who underwent partial or radical nephrectomy at our institution. 210 of these will be released for model training and validation, and the remaining 90 will be held out for objective model evaluation.


### 2019 ISBI: Segmentation of THoracic Organs at Risk in CT images [(SegTHOR)](https://competitions.codalab.org/competitions/21012)
TBD



### 2017 ISBI & MICCAI: Liver tumor segmentation challenge [(LiTS)](https://competitions.codalab.org/competitions/17094)
*Summary: The Liver Tumor Segmentation Benchmark (LiTS), Patrick Bilic et al. 201901 [(arxiv)](https://arxiv.org/abs/1901.04056)*

|Date|First Author |Title|Liver Dice|Tumor Dice|
|---|---|---|---|---|
|201709|[Xiaomeng Li](https://scholar.google.ca/citations?user=uVTzPpoAAAAJ&hl=zh-CN&oi=sra)| H-DenseUNet: Hybrid Densely Connected UNet for Liver and Tumor Segmentation from CT Volumes, [(paper)](https://arxiv.org/abs/1709.07330), [(Keras code)](https://github.com/xmengli999/H-DenseUNet) |0.961|0.722|


### 2012 MICCAI: Prostate MR Image Segmentation [(PROMISE12)](https://promise12.grand-challenge.org/)

|Date|First Author |Title|Whole Dice|Overall Score|
|---|---|---|---|---|
|201904|Anonymous|3D segmentation and 2D boundary network [(paper)](https://drive.google.com/file/d/1yGKeFNyXMajBQ1yebzXM2V-GiGf6GFBJ/view)|-|90.34|
|201902|Qikui Zhu|Boundary-weighted Domain Adaptive Neural Network for Prostate MR Image Segmentation [(paper)](https://arxiv.org/abs/1902.08128)|91.41|89.59|




## Others
### [2018 MICCAI Medical Segmentation Decathlon](http://medicaldecathlon.com/)

|Task|Data Info|Fabian Isensee et al. [(paper)](https://arxiv.org/abs/1809.10486)| Yingda Xia et al. [(paper)](https://arxiv.org/abs/1811.12506)|
|---|---|---|---|
|Brats|Multimodal multisite MRI data (FLAIR, T1w, T1gd,T2w),  (484 Training + 266 Testing) |0.68/0.48/0.68|0.675/0.45/0.68|    
|Heart|Mono-modal MRI (20 Training + 10 Testing) |0.93|0.925|
|Hippocampus head and body|Mono-modal MRI (263 Training + 131 Testing)|0.90/0.89|0.88/0.867|
|Liver & Tumor|Portal venous phase CT  (131 Training + 70 Testing)|0.95/0.74|0.95/0.714|
|Lung|CT (64 Training + 32 Testing)|0.69|0.52|
|Pancreas & Tumor|Portal venous phase CT (282 Training +139 Testing) |0.80/0.52|0.784/0.385|
|Prostate central gland and peripheral|Multimodal MR (T2, ADC) (32 Training + 16 Testing)|0.76/0.90|0.69/0.867|
|Hepatic vessel& Tumor| CT, (303 Training + 140 Testing)|0.63/0.69|-|
|Spleen|CT (41 Training + 20 Testing)|0.96|-|
|Colon|CT (41 Training + 20 Testing)|0.56|-|

> Only showing Dice Score.




## Awesome Open Source Tools

|Task|First Author|Title|Notes|
|---|---|---|---|
|Detection&Segmentation|[Paul F. Jaeger](https://scholar.google.ca/citations?user=9B9-8h0AAAAJ&hl=zh-CN&oi=sra)|Retina U-Net: Embarrassingly Simple Exploitation of Segmentation Supervision for Medical Object Detection, [(paper)](https://arxiv.org/abs/1811.08661), [(code)](https://github.com/pfjaeger/medicaldetectiontoolkit)|pytorch 0.4|
|Medical Image Analysis|[Eli Gibson](https://scholar.google.ca/citations?user=Wtp-1I8AAAAJ&hl=zh-CN&oi=sra) and [Wenqi Li](https://scholar.google.ca/citations?user=LFDQeh0AAAAJ&hl=zh-CN&oi=sra)|NiftyNet: a deep-learning platform for medical imaging [(paper)](https://arxiv.org/abs/1709.03485?context=cs.NE), [(code)](https://github.com/NifTK/NiftyNet)|Tensorflow 1.12|
|Segmentation|[Christian S. Perone](http://blog.christianperone.com/)|[MedicalTorch](https://medicaltorch.readthedocs.io/en/stable/)|pytorch>=0.4|
|awesome-semantic-segmentation|mrgloom|[awesome-semantic-segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)|3000+ stars|


## Loss functions for Imbalanced Problems

|Date|First Author|Title|Conference/Journal|
|---|---|---|---|
|201901|[Seyed Raein Hashemi](https://scholar.google.ca/citations?user=4VEP0fsAAAAJ&hl=en&oi=sra)|**Asymmetric Loss** Functions and Deep Densely Connected Networks for Highly Imbalanced Medical Image Segmentation: Application to Multiple Sclerosis Lesion Detection [(paper)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8573779)|IEEE Access|
|201812|[Hoel Kervadec](https://scholar.google.ca/citations?user=yeFGhfgAAAAJ&hl=zh-CN&oi=sra)|**Boundary loss** for highly unbalanced segmentation [(paper)](https://arxiv.org/abs/1812.07032), [(pytorch 1.0 code)](https://github.com/LIVIAETS/surface-loss)|[MIDL 2019](http://2019.midl.io/)|
|201810|[Nabila Abraham](https://scholar.google.ca/citations?user=OOvooSMAAAAJ&hl=zh-CN&oi=sra)|A Novel **Focal Tversky loss** function with improved Attention U-Net for lesion segmentation [(paper)](https://arxiv.org/abs/1810.07842)|[ISBI 2019](https://biomedicalimaging.org/2019/)|
|201808|[Ken C. L. Wong](https://scholar.google.ca/citations?hl=zh-CN&user=XjnODToAAAAJ&view_op=list_works&sortby=pubdate)|3D Segmentation with **Exponential Logarithmic Loss** for Highly Unbalanced Object Sizes [(paper)](https://arxiv.org/abs/1809.00076)|MICCAI 2018|
|201806|[Javier Ribera](https://scholar.google.ca/citations?user=TAaovakAAAAJ&hl=zh-CN&oi=sra)|**Weighted Hausdorff Distance:** Locating Objects Without Bounding Boxes [(paper)](https://arxiv.org/abs/1806.07564), [(pytorch code)](https://github.com/HaipengXiong/weighted-hausdorff-loss)|CVPR 2019|
|201708|[Tsung-Yi Lin](https://scholar.google.ca/citations?user=_BPdgV0AAAAJ&hl=zh-CN&oi=sra)|**Focal Loss** for Dense Object Detection [(paper)](https://arxiv.org/abs/1708.02002), [(code)](https://github.com/facebookresearch/Detectron)|ICCV, TPAMI|
|20170711|[Carole Sudre](https://scholar.google.ca/citations?user=14GfvB4AAAAJ&hl=zh-CN&oi=sra)|**Generalised Dice** overlap as a deep learning loss function for highly unbalanced segmentations [(paper)](https://arxiv.org/abs/1707.03237)|DLMIA 2017|
|20170703|[Lucas Fidon](https://scholar.google.ca/citations?user=GORojioAAAAJ&hl=zh-CN&oi=sra)|**Generalised Wasserstein Dice** Score for Imbalanced Multi-class Segmentation using Holistic Convolutional Networks [(paper)](https://arxiv.org/abs/1707.00478)|MICCAI 2017 BrainLes|
|201705|[Maxim Berman](https://scholar.google.ca/citations?user=RoOng2wAAAAJ&hl=zh-CN&oi=sra)|The **Lovász-Softmax loss:** A tractable surrogate for the optimization of the intersection-over-union measure in neural networks [(paper)](https://arxiv.org/abs/1705.08790), [(code)](https://github.com/bermanmaxim/LovaszSoftmax)|CVPR 2018|
|201701|[Seyed Sadegh Mohseni Salehi](https://scholar.google.ca/citations?user=hTWINokAAAAJ&hl=zh-CN&oi=sra)|**Tversky loss** function for image segmentation using 3D fully convolutional deep networks [(paper)](https://arxiv.org/abs/1706.05721)|MICCAI 2017 MLMI|
|201612|[Md Atiqur Rahman](https://scholar.google.ca/citations?user=tLPerVUAAAAJ&hl=zh-CN&oi=sra)|Optimizing **Intersection-Over-Union** in Deep Neural Networks for Image Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-319-50835-1_22)|2016 International Symposium on Visual Computing|
|201606|[Fausto Milletari](https://faustomilletari.github.io/)|**"Dice Loss"** V-net: Fully convolutional neural networks for volumetric medical image segmentation [(paper)](https://arxiv.org/abs/1606.04797), [(caffe code)](https://github.com/faustomilletari/VNet)|International Conference on 3D Vision|
|201511|[Tom Brosch](https://scholar.google.ca/citations?user=KChq7WIAAAAJ&hl=zh-CN&oi=sra)|**"Sensitivity-Specifity loss"** Deep Convolutional Encoder Networks for Multiple Sclerosis Lesion Segmentation [(paper)](http://www.rogertam.ca/Brosch_MICCAI_2015.pdf)|MICCAI 2015|
|201505|[Olaf Ronneberger](https://scholar.google.ca/citations?user=7jrO1NwAAAAJ&hl=zh-CN&oi=sra)|**"Weighted cross entropy"** U-Net: Convolutional Networks for Biomedical Image Segmentation [(paper)](https://arxiv.org/abs/1505.04597)|MICCAI 2015|
|201309|[Gabriela Csurka](https://scholar.google.ca/citations?user=PXm1lPAAAAAJ&hl=zh-CN&oi=sra)|What is a good evaluation measure for semantic segmentation? [(paper)](http://www.bmva.org/bmvc/2013/Papers/paper0032/paper0032.pdf)|BMVA 2013|

> Most of the corresponding code can be found [here](https://github.com/NifTK/NiftyNet/blob/dev/niftynet/layer/loss_segmentation.py).

## Contribute

Contributions are most welcome!

**[⬆ back to top](#Contents)**
