# Point-Cloud-Registration-and-Analysis
The repository mainly focuses on collecting recent works on point cloud registration, for sharing and better learning. Since many other tasks, like image matching and point cloud processing, are highly related to point cloud registration, these papers will be taken into account as well. In order to have a clear look at these fields, We simply classified the articles.This repository will continue to be updated.

labels of task: [cla.] for classfication, [reg.] for registration, [gen.] for shape generation, [nor.] for normal estimation

Statistics: 🔥 code is available & stars >= 100  |  ⭐ citation >= 50

---------------------------------------------------
## Point Cloud Registration
### Review
> what 

### Feature Extraction
* Point-based methods

* Voxel-based methods

* Generative model methods
> [CVPR 2020] PointGMM: a Neural GMM Network for Point Clouds. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156692)][[Code](https://github.com/amirhertz/pointgmm)] [reg. gen.]  
> [ECCV 2018] Hgmr: Hierarchical gaussian mixtures for adaptive 3d registration. [[Paper](https://link.springer.com/content/pdf/10.1007%2F978-3-030-01267-0_43.pdf)] [reg.]

### Unsupervised Methods
>

### Outliers Rejection
> [Com. ACM 1981] Random Sample Consensus: A Paradigm for Model Fitting with Applications to Image Analysis and Automated Cartography.(RANSAC) [[Paper](https://dl.acm.org/doi/pdf/10.1145/358669.358692)]
---------------------------------------------------------------
## Image Matching
### Find Correspondences
* Keypoint-based methods (Sparse)
> [CoRR 2020] D2D: Learning to find good correspondences for image matching and manipulation [[Paper](https://arxiv.org/pdf/2007.08480.pdf)]

* Dense methods
> [CVPR 2017] DeMoN: Depth and Motion Network for Learning Monocular Stereo. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100079)]

### End-to-end Methods

### Outlier Rejection
> [CVPR 2017] DSAC-Differentiable RANSAC for Camera Localization. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099750)]  
> [CVPR 2018] Learning to Find Good Correspondences. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yi_Learning_to_Find_CVPR_2018_paper.pdf)]
----------------------------------
## Point Cloud Analysis
* Point-based methods
> [CVPR 2019] PointConv: Deep Convolutional Networks on 3D Point Clouds.[[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_PointConv_Deep_Convolutional_Networks_on_3D_Point_Clouds_CVPR_2019_paper.pdf)][cla. seg.]  
> [CVPR 2018] PointNet

* Voxel-based methods
> SparseConvNet[[Code](https://github.com/facebookresearch/SparseConvNet)]

* Generative model methods
> [CVPR 2019] Nesti-net: Normal estimation for unstructured 3d pointclouds using convolutional neural networks. [[Papers](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ben-Shabat_Nesti-Net_Normal_Estimation_for_Unstructured_3D_Point_Clouds_Using_Convolutional_CVPR_2019_paper.pdf)] [nor.]  
> [TOG 2019] SDM-NET: Deep generative network for structured deformable mesh. [[Paper](https://dl.acm.org/doi/pdf/10.1145/3355089.3356488)] ][gen.]  
> [R&A Letters 2018] 3dmfv: Three-dimensional point cloud classification in real-time using convolutional neural networks. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8394990)] [cla.]
> 

### Review
> [IJCV 2020] Image Matching from Handcrafted to Deep Features: A Survey. [[Paper](https://link.springer.com/content/pdf/10.1007/s11263-020-01359-2.pdf)]  
> [SPM 2017] Geometric Deep Learning. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7974879)]
> 

### Else

---------------------------------------
## Point Cloud Dataset
* Synthetic dataset  
> ShapeNet: Large Scale Synthetic Objects  
> ModelNet  
> PartNet:Fine-grained; Instance-level; Hierarchical.  
> SceneNet: Large Scale Synthetic Scenes; 3D meshes
* Real world dataset
> 3DScan  
> ScanNet: Large-scale; RGBD scans; 3D camera poses; Instance-level segmentation.  
> KITTI: LiDAR data; labeled by 3D b.boxes.  
> Semantic KITTI: LiDAR data; labeled per point.  
> Waymo Open Dataset: LiDAR data; labeled by 3D b.boxes.


--------------------------------------
## Point Cloud Learning Resource
