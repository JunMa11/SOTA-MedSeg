# State-of-the-art medical image segmentation methods based on various challenges! (Updated 201910)

## Contents
**Head**
- 2019 MICCAI: Multimodal Brain Tumor Segmentation Challenge (BraTS2019) [(Ongoing!!!)](http://braintumorsegmentation.org/)
- 2019 MICCAI: 6-month Infant Brain MRI Segmentation from Multiple Sites (iSeg2019) [(Results)](http://iseg2019.web.unc.edu/evaluation-results/)
- 2019 MICCAI: Automatic Structure Segmentation for Radiotherapy Planning Challenge [(Results)](http://www.structseg-challenge.org/#/)
- 2018 MICCAI: Multimodal Brain Tumor Segmentation Challenge
- 2018 MICCAI: Ischemic stroke lesion segmentation
- 2018 MICCAI Grand Challenge on MR Brain Image Segmentation

**Chest & Abdomen**
- 2019 MICCAI: VerSe2019: Large Scale Vertebrae Segmentation Challenge [(Ongoing!!!)](https://verse2019.grand-challenge.org/Home/)
- 2019 MICCAI: Multi-sequence Cardiac MR Segmentation Challenge
- 2018 MICCAI: Left Ventricle Full Quantification Challenge 
- 2018 MICCAI: Atrial Segmentation Challenge
- 2019 MICCAI: Kidney Tumor Segmentation Challenge
- 2019 ISBI: Segmentation of THoracic Organs at Risk in CT images
- 2017 ISBI & MICCAI: Liver tumor segmentation challenge 
- 2012 MICCAI: Prostate MR Image Segmentation 

**Others**
- 2018 MICCAI Medical Segmentation Decathlon
- Awesome Open Source Tools
- Loss functions for class imbalanced Problems





## Head
- 2019 MICCAI: Multimodal Brain Tumor Segmentation Challenge (BraTS2019) [(Ongoing!!!)](http://braintumorsegmentation.org/)
- 2019 MICCAI: 6-month Infant Brain MRI Segmentation from Multiple Sites (iSeg2019) [(Results)](http://iseg2019.web.unc.edu/evaluation-results/)

### 2019 MICCAI: Structure Segmentation for Radiotherapy Planning [(StructSeg)](https://structseg2019.grand-challenge.org/)
> [Results](http://www.structseg-challenge.org/#/)

|Date|First Author |Title|Head & Neck OAR|Head & Neck GTV|Chest OAR|Chest GTV|
|---|---|---|---|---|---|---|
|20191001|Huai Chen|TBD|0.8109|0.6666|0.9011|0.5406|
|20191001|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|nnU-Net|0.7988|0.6398|0.9083|0.5343|
|20191001|Yujin Hu|TBD|0.7956|0.6245|0.9024|0.5447|
|20191001|Xuechen Liu|TBD|-|-|0.9066|-|


## Heart
### 2019 MICCAI: Multi-sequence Cardiac MR Segmentation Challenge [(MS-CMRSeg)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mscmrseg19/)
> Multi-sequence ventricle and myocardium segmentation.

|Date|First Author |Title|LV|Myo|RV|
|---|---|---|---|---|---|
|20190821|[Chen Chen](https://sites.google.com/view/morningchen-site/home)|Unsupervised Multi-modal Style Transfer for Cardiac MR Segmentation [(arxiv)](https://arxiv.org/pdf/1908.07344.pdf)|0.92|0.83|0.88|


## Chest and Abdomen
### [2019 Kaggle SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation)

|Date|First Author |Title|Dice|
|---|---|---|---|
|20190905|Aimoldin Anuar|SIIM-ACR Pneumothorax Challenge - 1st place solution [(pytorch)](https://github.com/sneddy/pneumothorax-segmentation)|0.8679|



### 2019 MICCAI: Kidney Tumor Segmentation Challenge [(KiTS19)](https://kits19.grand-challenge.org/)
**[Leaderboard (2019/07/30)](http://results.kits-challenge.org/miccai2019/)**

|Date|First Author |Title|Composite Dice|Kidney Dice|Tumor Dice|Remark|
|---|---|---|---|---|---|---|
|20190730|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|An attempt at beating the 3D U-Net [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/Isensee_1.pdf)|0.9123|0.9737|0.8509|1st Place|
|20190730|Xiaoshuai Hou |Cascaded Semantic Segmentation for Kidney and Tumor [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/PingAnTech_3.pdf)|0.9064|0.9674|0.8454|2nd Place|
|20190730|Guangrui Mu|Segmentation of kidney tumor by multi-resolution VB-nets [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/gr_6.pdf)|0.9025|0.9729|0.8321|3rd Place|
 



### 2019 ISBI: Segmentation of THoracic Organs at Risk in CT images [(SegTHOR)](https://competitions.codalab.org/competitions/21012)
|Date|First Author |Title|Esophagus|Heart|Trachea|Aorta|
|---|---|---|---|---|---|---|
|20190320|Miaofei Han|Segmentation of CT thoracic organs by multi-resolution VB-nets [(paper)](http://pagesperso.litislab.fr/cpetitjean/wp-content/uploads/sites/19/2019/04/SegTHOR2019_paper_1.pdf)|86|95|92|94|
|20190606|[Shadab Khan](https://scholar.google.ca/citations?user=HD4-OxgAAAAJ&hl=en&oi=ao)|Extreme Points Derived Conﬁdence Map as a Cue For Class-Agnostic Segmentation Using Deep Neural Network [(paper)](https://arxiv.org/pdf/1906.02421.pdf)|89.87|95.97|91.87|94|

> [Challenge results](http://pagesperso.litislab.fr/cpetitjean/wp-content/uploads/sites/19/2019/04/SegTHOR_presentation_2.pdf)


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
Recent results can be found [here](https://decathlon-10.grand-challenge.org/evaluation/results/).

|Task|Data Info|Fabian Isensee et al. [(paper)](https://arxiv.org/abs/1809.10486)| Yingda Xia et al. [(paper)](https://arxiv.org/abs/1811.12506)| [Qihang Yu](https://scholar.google.com/citations?hl=en&user=7zZdZxsAAAAJ&view_op=list_works&sortby=pubdate) on [Oct. 8](https://decathlon-10.grand-challenge.org/evaluation/results/95c498ae-8610-4e30-b220-84b4923a59ca/)|
|---|---|---|---|---|
|Brats|Multimodal multisite MRI data (FLAIR, T1w, T1gd,T2w),  (484 Training + 266 Testing) |0.68/0.48/0.68|0.675/0.45/0.68| 0.68/0.48/0.69|   
|Heart|Mono-modal MRI (20 Training + 10 Testing) |0.93|0.92|0.93|
|Hippocampus head and body|Mono-modal MRI (263 Training + 131 Testing)|0.90/0.89|0.88/0.87|0.89/0.88|
|Liver & Tumor|Portal venous phase CT  (131 Training + 70 Testing)|0.95/0.74|0.95/0.71|0.95/0.74|
|Lung|CT (64 Training + 32 Testing)|0.69|0.52|0.73|
|Pancreas & Tumor|Portal venous phase CT (282 Training +139 Testing) |0.80/0.52|0.78/0.39|0.81/0.56|
|Prostate central gland and peripheral|Multimodal MR (T2, ADC) (32 Training + 16 Testing)|0.76/0.90|0.69/0.867|0.75/0.89|
|Hepatic vessel& Tumor| CT, (303 Training + 140 Testing)|0.63/0.69|-|0.64/0.71|
|Spleen|CT (41 Training + 20 Testing)|0.96|-|0.97|
|Colon|CT (41 Training + 20 Testing)|0.56|-|0.53|

> Only showing Dice Score.

### Recent papers on Medical Segmentation Decathlon
|Date|First Author |Title|Score|
|---|---|---|---|
|20190606|Zhuotun Zhu|V-NAS: Neural Architecture Search for Volumetric Medical Image Segmentation [(arxiv)](https://arxiv.org/abs/1906.02817)|Lung tumor: 55.27; Pancreas and tumor: 79.94, 37.78 (4-fold CV)|



# Past Challenges (New submission closed)

### 2018 MICCAI: Multimodal Brain Tumor Segmentation Challenge[(BraTS)](https://www.med.upenn.edu/sbia/brats2018.html)
*Summary: Identifying the Best Machine Learning Algorithms for Brain Tumor Segmentation, Progression Assessment, and Overall Survival Prediction in the BRATS Challenge Spyridon Bakas et al. 201811, [(arxiv)](https://arxiv.org/abs/1811.02629)*

|Rank(18) |First Author |Title|Val. WT/EN/TC Dice|Test Val. WT/ET/TC Dice|
|---|---|---|---|---|
|1|Andriy Myronenko|3D MRI Brain Tumor Segmentation Using Autoencoder Regularization [(paper)](https://arxiv.org/pdf/1810.11654.pdf)|0.91/0.823/0.867|0.884/0.766/0.815|
|2|[Fabian Isensee](https://scholar.google.ca/citations?user=PjerEe4AAAAJ&hl=zh-CN&oi=ao)|No New-Net [(paper)](https://arxiv.org/abs/1809.10483)|0.913/0.809/0.863|0.878/0.779/0.806|
|3|[Richard McKinley](https://scholar.google.ca/citations?user=MVFfMZcAAAAJ&hl=zh-CN&oi=sra)|Ensembles of Densely-Connected CNNs with Label-Uncertainty for Brain Tumor Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-11726-9_40)|0.903/0.796/0.847|0.886/0.732/0.799|
|3|Chenhong Zhou|Learning Contextual and Attentive Information for Brain Tumor Segmentation [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-11726-9_44)|0.9095/0.8136/0.8651|0.8842/0.7775/0.7960|
|New|[Xuhua Ren](https://scholar.google.com/citations?user=V2ujH7IAAAAJ&hl=zh-CN)|Task Decomposition and Synchronization for Semantic Biomedical Image Segmentation [(paper)](https://arxiv.org/abs/1905.08720)|0.915/0.832/0.883|-|


### 2018 MICCAI: Ischemic stroke lesion segmentation [(ISLES )](http://www.isles-challenge.org/)

|Date |First Author |Title|Dice|
|---|---|---|---|
|20190605|Yu Chen|OctopusNet: A Deep Learning Segmentation Network for Multi-modal Medical Images [(paper)](https://arxiv.org/abs/1906.02031)|57.90 (5-fold CV)|
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
|3|Xuhua Ren|Ensembles of Multiple Scales, Losses and Models for Segmentation of Brain Area [(paper)](https://mrbrains18.isi.uu.nl/results/eight-label-segmentation-results/xuhuaren-2/) |9.872|
|201906|[Xuhua Ren](https://scholar.google.com/citations?user=V2ujH7IAAAAJ&hl=zh-CN)|Brain MR Image Segmentation in Small Dataset with Adversarial Defense and Task Reorganization [(arxiv )](https://arxiv.org/ftp/arxiv/papers/1906/1906.10400.pdf)|5 fold CV Dice: 84.46|

- Three Label Segmentation Results (201809)

|Rank |First Author |Title|GM/WM/CSF Dice|Score|
|---|---|---|---|---|
|1|Liyan Sun|Brain Tissue Segmentation Using 3D FCN with Multi-modality Spatial Attention [(paper)](https://mrbrains18.isi.uu.nl/results/three-label-segmentation-results/smartdsp-2/)|0.86/0.889/0.850|11.272|



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







## Awesome Open Source Tools

|Task|First Author|Title|Notes|
|---|---|---|---|
|Detection&Segmentation|[Paul F. Jaeger](https://scholar.google.ca/citations?user=9B9-8h0AAAAJ&hl=zh-CN&oi=sra)|Retina U-Net: Embarrassingly Simple Exploitation of Segmentation Supervision for Medical Object Detection, [(paper)](https://arxiv.org/abs/1811.08661), [(code)](https://github.com/pfjaeger/medicaldetectiontoolkit)|pytorch 0.4|
|Medical Image Analysis|[Eli Gibson](https://scholar.google.ca/citations?user=Wtp-1I8AAAAJ&hl=zh-CN&oi=sra) and [Wenqi Li](https://scholar.google.ca/citations?user=LFDQeh0AAAAJ&hl=zh-CN&oi=sra)|NiftyNet: a deep-learning platform for medical imaging [(paper)](https://arxiv.org/abs/1709.03485?context=cs.NE), [(code)](https://github.com/NifTK/NiftyNet)|Tensorflow 1.12|
|Segmentation|[Christian S. Perone](http://blog.christianperone.com/)|[MedicalTorch](https://medicaltorch.readthedocs.io/en/stable/)|pytorch>=0.4|
|awesome-semantic-segmentation|mrgloom|[awesome-semantic-segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)|3000+ stars|
|Segmentation|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|nnU-Net [(paper)](https://arxiv.org/abs/1904.08128) [(code)](https://github.com/MIC-DKFZ/nnUNet)|300+stars|


## Loss functions for Segmentation [(paper & code)](https://github.com/JunMa11/SegLoss)


## Contribute

Contributions are most welcome!

**[⬆ back to top](#Contents)**
