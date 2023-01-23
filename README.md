# State-of-the-art medical image segmentation methods based on various challenges! (Updated 2023-01)

## Contents
**Head and Neck**

- Brain Tumor Segmentation: BraTS [2019](https://www.med.upenn.edu/cbica/brats2019/data.html), [2020](https://www.med.upenn.edu/cbica/brats2020/), [2021](https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/brain-tumor-ai-challenge-2021), [2022](https://www.synapse.org/#!Synapse:syn27046444/wiki/616571)
- Intracranial Hemorrhage Segmentation Challenge on Non-Contrast head CT [(INSTANCE)](https://instance.grand-challenge.org/)
- Retinal Fundus Glaucoma Challenge Edition2 [(REFUGE2)](https://refuge.grand-challenge.org/) 
- [CATARACTS Semantic Segmentation](https://cataracts-semantic-segmentation2020.grand-challenge.org/) 
- Anatomical Brain Barriers to Cancer Spread: Segmentation from CT and MR Images [(ABCs)](https://abcs.mgh.harvard.edu/index.php/leader-board)
- 3D Head and Neck Tumor Segmentation: HECKTOR [2020](https://www.aicrowd.com/challenges/hecktor), [2021](https://www.aicrowd.com/challenges/miccai-2021-hecktor), [2022](https://hecktor.grand-challenge.org/)
- Cerebral Aneurysm Segmentation [(CADA)](https://cada-as.grand-challenge.org/Overview/) 
- Aneurysm Detection And segMenation Challenge 2020 [(ADAM)](http://adam.isi.uu.nl/) 
- Thyroid nodule segmentation and classification challenge [(TN-SCUI 2020)](https://tn-scui2020.grand-challenge.org/Home/)
- Automatic Lung Cancer Patient Management (LNDb) [(LNDb)](https://lndb.grand-challenge.org/Home/)
- 6-month Infant Brain MRI Segmentation from Multiple Sites: [iSeg2019](http://iseg2019.web.unc.edu/evaluation-results/), [cSeg2022](https://tarheels.live/cseg2022/)

**Heart**

- Automatic Evaluation of Myocardial Infarction from Delayed-Enhancement Cardiac MRI [(EMIDEC)](http://emidec.com/)
- Automated Segmentation of Coronary Arteries [(ASOCA)](https://asoca.grand-challenge.org/) [(Results)](https://asoca.grand-challenge.org/evaluation/challenge/leaderboard/)
- MyoPS 2020: Myocardial pathology segmentation combining multi-sequence CMR [(Homepage)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/myops20/)



**Chest & Abdomen**

- Fast and low-resource abdominal organ segmentation: FLARE [2021](https://flare.grand-challenge.org/), [2022](https://flare22.grand-challenge.org/)
- Multi-Modality Abdominal Multi-Organ Segmentation Challenge [(AMOS22)](https://amos22.grand-challenge.org/)  [(Results)](https://amos22.grand-challenge.org/final-ranking/)
- Kidney Tumor Segmentation Challenge: [KiTS19](https://kits19.grand-challenge.org/home/), [(KiTS21)](https://kits21.grand-challenge.org/) 
- Large Scale Vertebrae Segmentation Challenge: [VerSe2019](https://verse2019.grand-challenge.org/VerSe_at_MICCAI19/), [VerSe2020](https://verse2020.grand-challenge.org/)



**Others**
- 2018 MICCAI: Medical Segmentation Decathlon [(MSD)](http://medicaldecathlon.com/) [(Results)](https://decathlon-10.grand-challenge.org/evaluation/challenge/leaderboard/)
- 2020 MICCAI: Quantification of Uncertainties in Biomedical Image Quantification Challenge [(QUBIQ)](https://qubiq.grand-challenge.org/) [(Results)](https://qubiq.grand-challenge.org/evaluation/challenge/leaderboard/)
- Awesome Open Source Tools
- Loss Odyssey in Medical Image Segmentation



## Ongoing Challenges

## Intracranial Hemorrhage Segmentation Challenge on Non-Contrast head CT [(INSTANCE)](https://instance.grand-challenge.org/)

| Date     | First Author    | Title                                                        | DSC  | NSD   | RVD | HD | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ----  | ------------------------ |
| 202301 | 	Xiangyu Li | The state-of-the-art 3D anisotropic intracranial hemorrhage segmentation on non-contrast head CT: The INSTANCE challenge  [(paper)](https://arxiv.org/abs/2301.03281) | 0.7912 | 0.5026 | 0.21 | 29.02 | Summary paper |

## 2022 MICCAI: Brain Tumor Segmentation [(BraTS2022)](https://www.synapse.org/#!Synapse:syn27046444/wiki/616571)

| Date     | First Author    | Title                                                        | ET DSC  | TC DSC   | WT DSC                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | 
| 202209 | Ramy A. Zeineldin	| Multimodal CNN Networks for Brain Tumor Segmentation in MRI: A BraTS 2022 Challenge Solution [(paper)](https://arxiv.org/abs/2212.09310)  | 0.8438 | 0.8753 | 0.9271 |



## 2022 MICCAI: Multi-Modality Abdominal Multi-Organ Segmentation Challenge [(AMOS22)](https://amos22.grand-challenge.org/)  [(Results)](https://amos22.grand-challenge.org/final-ranking/)

| Date     | First Author    | Title                                                        | Task 1-DSC  | Task 1-NSD   | Task 2-DSC | Task 2-NSD | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ----  | ------------------------ |
| 202209 | 	Fabian Isensee, Constantin Ulrich and Tassilo Wald     | Extending nnU-Net is all you need  [(paper)](https://arxiv.org/abs/2208.10791) [(code)](https://github.com/MIC-DKFZ/nnUNet) | TBA | TBA | TBA | TBA | 1st Place in MICCAI 2022 |


## 2021 ISBI: MitoEM Challenge: Large-scale 3D Mitochondria Instance Segmentation ([MitoEM](https://mitoem.grand-challenge.org/)) ([Results](https://mitoem.grand-challenge.org/evaluation/challenge/leaderboard/))

| Date     | First Author    | Title                                                        | MitoEM-R  | MitoEM-H   | Average |  Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ----  | ------------------------ |
| 202104 | Mingxing Li     | Advanced Deep Networks for 3D Mitochondria Instance Segmentation  [(paper)](https://arxiv.org/abs/2104.07961) [(code)](https://github.com/Limingxing00/MitoEM2021-Challenge) | 0.851 | 0.829 | 0.840 | 1st Place in ISBI 2021 |


## 2021 MICCAI: Fast and Low GPU memory Abdominal oRgan sEgmentation [(FLARE)](https://flare.grand-challenge.org/) [(Results)](https://flare.grand-challenge.org/Awards/)

| Date     | First Author    | Title                                                        | DSC  | NSD   | Time | GPU Memory | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ----  | ------------------------ |
| 202110 | Fan Zhang     | Efficient Context-Aware Network for Abdominal Multi-organ Segmentation  [(paper)](https://github.com/JunMa11/FLARE/blob/main/FLARE21/ShortPapers/fosun_aitrox.pdf) [(code)](https://github.com/Shanghai-Aitrox-Technology/EfficientSegmentation) | 0.895 | 0.796 | 9.32 | 1177 | 1st Place in MICCAI 2021 |

 
## 2021 MICCAI: Kidney Tumor Segmentation Challenge [(KiTS)](https://kits21.grand-challenge.org/)  [(Results)](https://kits21.grand-challenge.org/evaluation/challenge/leaderboard/)

| Date     | First Author    | Title                                                        | DSC  | NSD   | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ------------------------ |
| 202110 | Zhaozhong Chen     | A Coarse-to-fine Framework for The 2021 Kidney and Kidney Tumor Segmentation Challenge [(paper)](https://openreview.net/forum?id=6Py5BNBKoJt)        | 0.9077 | 0.8262 | 1st Place in MICCAI 2021 |


## 2020 MICCAI: Cerebral Aneurysm Segmentation [(CADA)](https://cada-as.grand-challenge.org/Overview/)  [(Results)](https://cada-as.grand-challenge.org/FinalRanking/)

| Date     | First Author    | Title                                                        | IoU  | HD   | MD   | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ------------------------ |
| 20201008 | Mediclouds     | TBA        | 0.758 | 2.866 | 1.618 | 1st Place in MICCAI 2020 |
| 20201008 | Jun Ma          | Exploring Large Context for Cerebral Aneurysm Segmentation [(arxiv)](https://arxiv.org/abs/2012.15136) [(Code)](https://github.com/JunMa11/ADAM2020) | 0.759 | 4.967  | 3.535 | 2nd Place in MICCAI 2020 |

## 2020 MICCAI: Automatic Evaluation of Myocardial Infarction from Delayed-Enhancement Cardiac MRI [(EMIDEC)](http://emidec.com/)

| Date     | First Author    | Title                                                        | Myo  | Infarction   | Re-flow   | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ------------------------ |
| 20201008 | Yichi Zhang     | Cascaded Convolutional Neural Network for Automatic Myocardial Infarction Segmentation from Delayed-Enhancement Cardiac MRI [(arxiv)](https://arxiv.org/abs/2012.14128)       | 0.8786 | 0.7124 | 0.7851 | 1st Place in MICCAI 2020 |
| 20201008 | Jun Ma          | Cascaded Framework for Automatic Evaluation of Myocardial Infarction from Delayed-Enhancement Cardiac MRI [(arxiv)](https://arxiv.org/abs/2012.14556) | 0.8628 | 0.6224  | 0.7776 | 2nd Place in MICCAI 2020 |
| 20201008 | Xue Feng        |  Automatic Scar Segmentation from DE-MRI Using 2D Dilated UNet with Rotation-based Augmentation [(paper)](http://emidec.com/downloads/papers/paper-24.pdf) | 0.8356 | 0.4568  | 0.7222 | 3rd Place in MICCAI 2020 |

> Metrics: DSC

## Aneurysm Detection And segMenation Challenge 2020 [(ADAM)](http://adam.isi.uu.nl/) [(Results)](http://adam.isi.uu.nl/results/results-miccai-2020/)



| Date     | First Author    | Title                                                        | DSC  | MHD   | VS   | Remark                   |
| -------- | --------------- | ------------------------------------------------------------ | ---- | ----- | ---- | ------------------------ |
| 20201008 | Jun Ma          | Loss Ensembles for Intracranial Aneurysm Segmentation: An Embarrassingly Simple Method [(Code)](https://github.com/JunMa11/ADAM2020) | 0.41 | 8.96  | 0.50 | 1st Place in MICCAI 2020 |
| 20201008 | Yuexiang Li     | Automatic Aneurysm Segmentation via 3D U-Net Ensemble        | 0.40 | 8.67  | 0.48 | 2nd Place in MICCAI 2020 |
| 20201008 | Riccardo De Feo | Multi-loss CNN ensemblesfor aneurysm segmentation            | 0.28 | 18.13 | 0.39 | 3rd Place in MICCAI 2020 |





## Multi-Centre, Multi-Vendor & Multi-Disease Cardiac Image Segmentation Challenge [(M&Ms)](https://www.ub.edu/mnms/) [(Results)](https://www.ub.edu/mnms/)



| Date     | First Author | Title                                                        | LV    | MYO   | RV    | Remark                   |
| -------- | ------------ | ------------------------------------------------------------ | ----- | ----- | ----- | ------------------------ |
| 20201004 | Peter Full   | The effect of Data Augmentation on Robustness against Domain Shifts in cMRI Segmentation | 0.910 | 0.849 | 0.884 | 1st Place in MICCAI 2020 |
| 20201004 | Yao Zhang    | Semi-Supervised Cardiac Image Segmentation via Label Propagation and Style Transfer | 0.906 | 0.840 | 0.878 | 2nd Place in MICCAI 2020 |
| 20201004 | Jun Ma       | Histogram Matching Augmentation for Domain Adaptation [(code)](https://github.com/JunMa11/HM_DataAug) | 0.902 | 0.835 | 0.874 | 3rd Place in MICCAI 2020 |

> Dice values are reported. Video records are available on [pathable](https://miccai2020.pathable.co/meetings/virtual/9s68Ygc7KbQqDg3ZR). All the papers are in press

## 2020 MICCAI: 3D Head and Neck Tumor Segmentation in PET/CT [(HECKTOR 2020)](https://www.aicrowd.com/challenges/hecktor). [(Results)](https://www.aicrowd.com/challenges/miccai-2020-hecktor/leaderboards)

| Date     | First Author | Title                                                        | DSC    | Remark                   |
| -------- | ------------ | ------------------------------------------------------------ | ------ | ------------------------ |
| 20201004 | Andrei Iantsen  | Squeeze-and-Excitation Normalization for Automated Delineation of Head and Neck Primary Tumors in Combined PET and CT Images  [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-67194-5_4) | 0.759 | 1st Place in MICCAI 2020 |
| 20201004 | Jun Ma    | Combining CNN and Hybrid Active Contours for Head and Neck Tumor Segmentation in CT and PET Images [(paper)](https://link.springer.com/chapter/10.1007/978-3-030-67194-5_7)  | 0.752 | 2nd Place in MICCAI 2020 |


## 2020 MICCAI: Thyroid nodule segmentation and classification challenge [(TN-SCUI 2020)](https://tn-scui2020.grand-challenge.org/Home/). [(Results)](https://tn-scui2020.grand-challenge.org/evaluation/leaderboard/)

| Date     | First Author | Title                                                        | IoU    | Remark                   |
| -------- | ------------ | ------------------------------------------------------------ | ------ | ------------------------ |
| 20201004 | Mingyu Wang  | A Simple Cascaded Framework for Automatically Segmenting Thyroid Nodules  [(code)](https://github.com/WAMAWAMA/TNSCUI2020-Seg-Rank1st) | 0.8254 | 1st Place in MICCAI 2020 |
| 20201004 | Huai Chen    | LRTHR-Net: A Low-Resolution-to-High-Resolution Framework to Iteratively Refine the Segmentation of Thyroid Nodule in Ultrasound Images | 0.8196 | 2nd Place in MICCAI 2020 |
| 20201004 | Zhe Tang     | Coarse to Fine Ensemble Network for Thyroid Nodule Segmentation | 0.8194 | 3rd Place in MICCAI 2020 |

> Video  records are available on [pathable](https://miccai2020.pathable.co/meetings/virtual/PCm5naT39rprt2MXC)

## Endoscopy Computer Vision Challenge [(EndoCV2020)](https://endocv.grand-challenge.org/)

| Date     | First Author | Title                                                        | Avg F1 and F2    | Remark                   |
| -------- | ------------ | ------------------------------------------------------------ | ------ | ------------------------ |
| 202004 | Vajira Thambawita  | DivergentNets: Medical Image Segmentation by Network Ensemble [(paper)](http://ceur-ws.org/Vol-2886/paper3.pdf)  [(code)](https://github.com/vlbthambawita/divergent-nets) | 0.823 | 1st Place in ISBI EndoCV 2020 |

### 2020 ICIAR: Automatic Lung Cancer Patient Management (LNDb) [(LNDb)](https://lndb.grand-challenge.org/Home/)
> [Results](https://lndb.grand-challenge.org/evaluation/results/)

|Date|First Author |Title|IoU|Remark|
|---|---|---|---|---|
|20200625|Alexandr G. Rassadin|Deep Residual 3D U-Net for Joint Segmentation and Texture Classification of Nodules in Lung [(arxiv)](https://arxiv.org/abs/2006.14215)|0.5221|1st Place in Seg. Task|


## Challenges on Open Leaderboard Phase







### 2019 MICCAI: Kidney Tumor Segmentation Challenge [(KiTS19)](https://kits19.grand-challenge.org/)

**[Leaderboard (2019/07/30)](http://results.kits-challenge.org/miccai2019/)**

|Date|First Author |Title|Composite Dice|Kidney Dice|Tumor Dice|
|---|---|---|---|---|---|
|202004|[Fabian Isensee](https://scholar.google.com.hk/citations?user=PjerEe4AAAAJ&hl=en&oi=sra)|Automated Design of Deep Learning Methods for Biomedical Image Segmentation [(arxiv)](https://arxiv.org/abs/1904.08128) |0.9168|0.9793|0.8542|
|20190730|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|An attempt at beating the 3D U-Net [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/Isensee_1.pdf)|0.9123|0.9737|0.8509|
|20190730|Xiaoshuai Hou |Cascaded Semantic Segmentation for Kidney and Tumor [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/PingAnTech_3.pdf)|0.9064|0.9674|0.8454|
|20190730|Guangrui Mu|Segmentation of kidney tumor by multi-resolution VB-nets [(paper)](http://results.kits-challenge.org/miccai2019/manuscripts/gr_6.pdf)|0.9025|0.9729|0.8321|


### 2017 ISBI & MICCAI: Liver tumor segmentation challenge [(LiTS)](https://competitions.codalab.org/competitions/17094)
*Summary: The Liver Tumor Segmentation Benchmark (LiTS), Patrick Bilic et al. 201901 [(arxiv)](https://arxiv.org/abs/1901.04056)*

|Date|First Author |Title|Liver Per Case Dice|Liver Global Dice|Tumor Per Case Dice|Tumor Global Dice|
|---|---|---|---|---|---|---|
|202004|[Fabian Isensee](https://scholar.google.com.hk/citations?user=PjerEe4AAAAJ&hl=en&oi=sra)|Automated Design of Deep Learning Methods for Biomedical Image Segmentation [(arxiv)](https://arxiv.org/abs/1904.08128) |0.967|0.970|0.763|0.858|
|201909|[Xudong Wang](https://scholar.google.com.hk/citations?user=RyS4ueAAAAAJ&hl=zh-CN&oi=sra)|Volumetric Attention for 3D Medical Image Segmentation and Detection [(MICCAI2019)](https://link.springer.com/chapter/10.1007/978-3-030-32226-7_20)|-|-|0.741|-|
|201908|Jianpeng Zhang|Light-Weight Hybrid Convolutional Network for Liver Tumor Segmentation [(IJCAI 2019)](https://doi.org/10.24963/ijcai.2019/593)|0.965|0.968|0.730|0.820|
|202007|Youbao Tang|E^2Net: An Edge Enhanced Network for Accurate Liver and Tumor Segmentation on CT Scans [(arXiv)](https://arxiv.org/abs/2007.09791v1)|0.966|0.968|0.724|0.829|
|201709|[Xiaomeng Li](https://scholar.google.ca/citations?user=uVTzPpoAAAAJ&hl=zh-CN&oi=sra)| H-DenseUNet: Hybrid Densely Connected UNet for Liver and Tumor Segmentation from CT Volumes, [(TMI)](https://arxiv.org/abs/1709.07330), [(Keras code)](https://github.com/xmengli999/H-DenseUNet) |0.961|0.965|0.722|0.824|



### 2012 MICCAI: Prostate MR Image Segmentation [(PROMISE12)](https://promise12.grand-challenge.org/)

|Date|First Author |Title|Whole Dice|Overall Score|
|---|---|---|---|---|
|201904|Anonymous|3D segmentation and 2D boundary network [(paper)](https://drive.google.com/file/d/1yGKeFNyXMajBQ1yebzXM2V-GiGf6GFBJ/view)|-|90.34|
|201902|Qikui Zhu|Boundary-weighted Domain Adaptive Neural Network for Prostate MR Image Segmentation [(paper)](https://arxiv.org/abs/1902.08128)|91.41|89.59|




## Others
### [2018 MICCAI Medical Segmentation Decathlon](http://medicaldecathlon.com/)
Recent results can be found [here](https://decathlon-10.grand-challenge.org/evaluation/results/).

|Task|Data Info|Fabian Isensee et al. [(paper)](https://arxiv.org/abs/1809.10486)|[nnUNet v2](https://github.com/MIC-DKFZ/nnUNet) | [Qihang Yu](https://scholar.google.com/citations?hl=en&user=7zZdZxsAAAAJ&view_op=list_works&sortby=pubdate) et al. [(paper)](https://arxiv.org/abs/1912.09628)|
|---|---|---|---|---|
|Brats|Multimodal multisite MRI data (FLAIR, T1w, T1gd,T2w),  (484 Training + 266 Testing) |0.68/0.48/0.68|68/46.8/68.46| 67.6/48.6/69.7|
|Heart|Mono-modal MRI (20 Training + 10 Testing) |0.93|96.74|92.49|
|Hippocampus head and body|Mono-modal MRI (263 Training + 131 Testing)|0.90/0.89|90/88.69|89.37/87.96|
|Liver & Tumor|Portal venous phase CT  (131 Training + 70 Testing)|0.95/0.74|95.75/75.97|94.98/72.89|
|Lung|CT (64 Training + 32 Testing)|0.69|73.97|70.44|
|Pancreas & Tumor|Portal venous phase CT (282 Training +139 Testing) |0.80/0.52|81.64/52.78|80.76/54.41|
|Prostate central gland and peripheral|Multimodal MR (T2, ADC) (32 Training + 16 Testing)|0.76/0.90|76.59/89.62|74.88/88.75|
|Hepatic vessel& Tumor| CT, (303 Training + 140 Testing)|0.63/0.69|66.46/71.78|64.73/71|
|Spleen|CT (41 Training + 20 Testing)|0.96|97.43|96.28|
|Colon|CT (41 Training + 20 Testing)|0.56|58.33|58.90|

> Only showing Dice Score.

### Recent papers on Medical Segmentation Decathlon
|Date|First Author |Title|Score|
|---|---|---|---|
|20181129|Yingda Xia|3D Semi-Supervised Learning with Uncertainty-Aware Multi-View Co-Training [(paper)](https://arxiv.org/abs/1811.12506)|no test set score|
|20190606|Zhuotun Zhu|V-NAS: Neural Architecture Search for Volumetric Medical Image Segmentation [(arxiv)](https://arxiv.org/abs/1906.02817)|Lung tumor: 55.27; Pancreas and tumor: 79.94, 37.78 (4-fold CV)|


# Past Challenges (New submission closed)
### 2020 MICCAI-MyoPS: Myocardial pathology segmentation combining multi-sequence CMR [(MyoPS 2020)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/myops20/)



| Date     | First Author | Title                                                        | Scar          | Scar+Edema    | Remark                   |
| -------- | ------------ | ------------------------------------------------------------ | ------------- | ------------- | ------------------------ |
| 20201004 | Shuwei Zhai  | Myocardial Edema and Scar Segmentation using a Coarse-to-Fine Framework with Weighted Ensemble [(paper in press)](https://arxiv.org/abs/2006.14215) | 0.672 (0.244) | 0.731 (0.109) | 1st Place in MICCAI 2020 |



### 2019 MICCAI: Structure Segmentation for Radiotherapy Planning [(StructSeg)](https://structseg2019.grand-challenge.org/)

> [Results](http://www.structseg-challenge.org/#/)

| Date     | First Author                                                 | Title   | Head & Neck OAR | Head & Neck GTV | Chest OAR | Chest GTV |
| -------- | ------------------------------------------------------------ | ------- | --------------- | --------------- | --------- | --------- |
| 20191001 | Huai Chen                                                    | TBD     | 0.8109          | 0.6666          | 0.9011    | 0.5406    |
| 20191001 | [Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en) | nnU-Net | 0.7988          | 0.6398          | 0.9083    | 0.5343    |
| 20191001 | Yujin Hu                                                     | TBD     | 0.7956          | 0.6245          | 0.9024    | 0.5447    |
| 20191001 | Xuechen Liu                                                  | TBD     | -               | -               | 0.9066    | -         |





### 2019 MICCAI: Multi-sequence Cardiac MR Segmentation Challenge [(MS-CMRSeg)](http://www.sdspeople.fudan.edu.cn/zhuangxiahai/0/mscmrseg19/)

> Multi-sequence ventricle and myocardium segmentation.

|Date|First Author |Title|LV|Myo|RV|
|---|---|---|---|---|---|
|20190821|[Chen Chen](https://sites.google.com/view/morningchen-site/home)|Unsupervised Multi-modal Style Transfer for Cardiac MR Segmentation [(arxiv)](https://arxiv.org/pdf/1908.07344.pdf)|0.92|0.83|0.88|

### [2019 Kaggle SIIM-ACR Pneumothorax Segmentation](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation)

|Date|First Author |Title|Dice|
|---|---|---|---|
|20190905|Aimoldin Anuar|SIIM-ACR Pneumothorax Challenge - 1st place solution [(pytorch)](https://github.com/sneddy/pneumothorax-segmentation)|0.8679|


### 2019 ISBI: Segmentation of THoracic Organs at Risk in CT images [(SegTHOR)](https://competitions.codalab.org/competitions/21145)
|Date|First Author |Title|Esophagus|Heart|Trachea|Aorta|
|---|---|---|---|---|---|---|
|20190320|Miaofei Han|Segmentation of CT thoracic organs by multi-resolution VB-nets [(paper)](http://pagesperso.litislab.fr/cpetitjean/wp-content/uploads/sites/19/2019/04/SegTHOR2019_paper_1.pdf)|86|95|92|94|
|20190606|[Shadab Khan](https://scholar.google.ca/citations?user=HD4-OxgAAAAJ&hl=en&oi=ao)|Extreme Points Derived Conﬁdence Map as a Cue For Class-Agnostic Segmentation Using Deep Neural Network [(paper)](https://arxiv.org/pdf/1906.02421.pdf)|89.87|95.97|91.87|94|

> [Challenge results](http://pagesperso.litislab.fr/cpetitjean/wp-content/uploads/sites/19/2019/04/SegTHOR_presentation_2.pdf)


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
|Detection&Segmentation|[Paul F. Jaeger](https://scholar.google.ca/citations?user=9B9-8h0AAAAJ&hl=zh-CN&oi=sra)|Retina U-Net: Embarrassingly Simple Exploitation of Segmentation Supervision for Medical Object Detection, [(paper)](https://arxiv.org/abs/1811.08661), [(code)](https://github.com/pfjaeger/medicaldetectiontoolkit)|pytorch|
|Medical Image Analysis|Many excellent contributors|MONAI: **M**edical **O**pen **N**etwork for **AI** [(code)](https://github.com/Project-MONAI/MONAI)|pytorch|
|Segmentation|[Christian S. Perone](http://blog.christianperone.com/)|[MedicalTorch](https://medicaltorch.readthedocs.io/en/stable/)|pytorch|
|Segmentation|[Fabian Isensee](https://scholar.google.com/citations?user=PjerEe4AAAAJ&hl=en)|nnU-Net [(paper)](https://arxiv.org/abs/1904.08128) [(code)](https://github.com/MIC-DKFZ/nnUNet)|pytorch|
|MedImgIO| [Fernando Pérez García](https://uk.linkedin.com/in/fernandoperezgarcia)|TorchIO: tools for loading, augmenting and writing 3D medical images on PyTorch [(code)](https://github.com/fepegar/torchio)|pytorch|
|Segmentation|[DLinRadiology](https://twitter.com/DLinRadiology)|MegSeg: a free segmentation tool for radiological images (CT and MRI)|[homepage](http://medicalsegmentation.com/)|
|Segmentation|Adaloglou Nikolaos|A 3D multi-modal medical image segmentation library in PyTorch [(code)](https://github.com/black0017/MedicalZooPytorch)|pytorch|

## Segmentation Loss Odyssey (paper & code)](https://github.com/JunMa11/SegLoss)


## Contribute

Contributions are most welcome!

**[⬆ back to top](#Contents)**
