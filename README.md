# Point-Cloud-Registration-and-Analysis
The repository mainly focuses on collecting recent works on point cloud registration, for sharing and better learning. Since many other tasks, like image matching and point cloud processing, are highly related to point cloud registration, these papers will be taken into account as well. In order to have a clear look at these fields, We simply classified the articles.This repository will continue to be updated.

labels of task: [cla.] for classfication | [reg.] for registration | [def] for shape deformation | [gen.] for shape generation | [nor.] for normal estimation | [shot.] for few/one/zero-shot learning | [recon.] for reconstruction.

Statistics: 🔥 code is available & stars >= 100  |  ⭐ citation >= 50

---------------------------------------------------
## Point Cloud Registration
### Review
> what 

### Feature Extraction
* Point-based methods

* Voxel-based methods

* Generative model methods
> [2020 CVPR] PointGMM: a Neural GMM Network for Point Clouds. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156692) [[Code](https://github.com/amirhertz/pointgmm) [reg. gen.]  
> [2018 ECCV] Hgmr: Hierarchical gaussian mixtures for adaptive 3d registration. [Paper](https://link.springer.com/content/pdf/10.1007%2F978-3-030-01267-0_43.pdf) [reg.]

* Lattice method

* Tangent convolution method

### Unsupervised Methods
>

### Outliers Rejection
> [1981 Com. ACM] Random Sample Consensus: A Paradigm for Model Fitting with Applications to Image Analysis and Automated Cartography.(RANSAC) [Paper](https://dl.acm.org/doi/pdf/10.1145/358669.358692)
---------------------------------------------------------------
## Point Cloud Analysis
* Point-based methods
> [2019 CVPR] PointConv: Deep Convolutional Networks on 3D Point Clouds.[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_PointConv_Deep_Convolutional_Networks_on_3D_Point_Clouds_CVPR_2019_paper.pdf)][cla. seg.]  
> [2018 CVPR] PointNet

* Voxel-based methods
> SparseConvNet[[Code](https://github.com/facebookresearch/SparseConvNet)]  
> [2018 CVPR] SyncSpecCNN: Synchronized Spectral CNN for 3D Shape Segmentation. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100180) [seg.]

* Generative model methods
> [2019 CVPR] Nesti-net: Normal estimation for unstructured 3d pointclouds using convolutional neural networks. [[Papers](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ben-Shabat_Nesti-Net_Normal_Estimation_for_Unstructured_3D_Point_Clouds_Using_Convolutional_CVPR_2019_paper.pdf)] [nor.]  
> [2019 Graphic] SDM-NET: deep generative network for structured deformable mesh. [Paper](https://dl.acm.org/doi/pdf/10.1145/3355089.3356488) [def.]  
> [2019 TOG] SDM-NET: Deep generative network for structured deformable mesh. [Paper](https://dl.acm.org/doi/pdf/10.1145/3355089.3356488) [gen.]  
> [2018 R&A Letters] 3dmfv: Three-dimensional point cloud classification in real-time using convolutional neural networks. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8394990) [cla.]
> 

* Spherical CNN
>

* Else
> [2020 ICLR] Learning to Group: A Bottom-Up Framework for 3D Part Discovery in Unseen Categories. [Paper]()  
> [2018 ACM Graphic] Deep part induction from articulated object pairs. [Paper](https://dl.acm.org/doi/pdf/10.1145/3272127.3275027) [shot.]


### Review
> [2020 IJCV] Image Matching from Handcrafted to Deep Features: A Survey. [Paper](https://link.springer.com/content/pdf/10.1007/s11263-020-01359-2.pdf)  
> [2017 SPM] Geometric Deep Learning. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7974879)
> 

### Else
> [2019 ICCV] Deep Mesh Reconstruction From Single RGB Images via Topology Modification Networks.[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9009447)  
> [2019 CVPR] Occupancy Networks: Learning 3D Reconstruction in Function Space. [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Mescheder_Occupancy_Networks_Learning_3D_Reconstruction_in_Function_Space_CVPR_2019_paper.pdf) [recon.]  
> [2018 NIPS] Learning to Reconstruct Shapes from Unseen Classes. [Paper](http://papers.nips.cc/paper/7494-learning-to-reconstruct-shapes-from-unseen-classes.pdf) [recon.]
> [2017 NIPS] MarrNet: 3D Shape Reconstruction via 2.5D Sketches. [Paper](http://papers.nips.cc/paper/6657-marrnet-3d-shape-reconstruction-via-25d-sketches.pdf) [recon.]  
> 

---------------------------------------
## Image Matching
### Find Correspondences
* Keypoint-based methods (Sparse)
> [2020 CoRR] D2D: Learning to find good correspondences for image matching and manipulation [Paper](https://arxiv.org/pdf/2007.08480.pdf)

* Dense methods
> [2017 CVPR] DeMoN: Depth and Motion Network for Learning Monocular Stereo. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8100079)

### End-to-end Methods

### Outlier Rejection
> [2018 CVPR] Learning to Find Good Correspondences. [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yi_Learning_to_Find_CVPR_2018_paper.pdf)  
> [2017 CVPR] DSAC-Differentiable RANSAC for Camera Localization. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8099750)  

###Review
> [2020 IJCV] Image Matching from Handcrafted to Deep Features: A Survey. [Paper](https://link.springer.com/content/pdf/10.1007/s11263-020-01359-2.pdf)
 
----------------------------------
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
