# MVS
> Reconstructing a 3D World from 2D Images

## :bookmark_tabs:	 Learning-based MVS methods
:books:  [Preliminaries of MVS](Preliminaries/)    
:star:  Datasets: *DTU, BlendedMVS, Tanks and Temples, ETH3D*  
> * must see  
  
|  | Abbreviation & Notes | Title | Years | Paper & Code | Rating |
| :-------: | :-------: | :-------: | :---------: | :-------: | :-------: |
| 1 | [MVSNet*](Networks/MVSNet.md) | MVSNet: Depth Inference for Unstructured Multi-View Stereo | ECCV 2018 | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yao_Yao_MVSNet_Depth_Inference_ECCV_2018_paper.pdf)<br>[Supp.](https://yoyo000.github.io/papers/yao2018mvsnet_supp.pdf)<br>[Code1](https://github.com/YoYo000/MVSNet)<br>[Code2](https://github.com/xy-guo/MVSNet_pytorch)| ★★★★★ |  
| 2 | [R-MVSNet*](Networks/R-MVSNet.md) | Recurrent Mvsnet for High-Resolution Multi-View Stereo Depth Inference | CVPR 2019 | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yao_Recurrent_MVSNet_for_High-Resolution_Multi-View_Stereo_Depth_Inference_CVPR_2019_paper.pdf) <br>[Supp.](https://openaccess.thecvf.com/content_CVPR_2019/supplemental/Yao_Recurrent_MVSNet_for_CVPR_2019_supplemental.pdf)<br>[Code](https://github.com/YoYo000/MVSNet)| ★★★☆ |  
| 3 | [CasMVSNet*](Networks/CasMVSNet.md) | Cascade Cost Volume for High-Resolution Multi-View Stereo and Stereo Matching | CVPR 2020 | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Cascade_Cost_Volume_for_High-Resolution_Multi-View_Stereo_and_Stereo_Matching_CVPR_2020_paper.pdf)<br>[Code](https://github.com/alibaba/cascade-stereo/tree/master/CasMVSNet)| ★★★★★ | 
| 4 | UCSNet | Deep Stereo using Adaptive Thin Volume Representation with Uncertainty Awareness | CVPR 2020 | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_Deep_Stereo_Using_Adaptive_Thin_Volume_Representation_With_Uncertainty_Awareness_CVPR_2020_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content_CVPR_2020/supplemental/Cheng_Deep_Stereo_Using_CVPR_2020_supplemental.pdf)<br>[Code](https://github.com/touristCheng/UCSNet)| ★★★☆ |  
| 5 | CVPMVSNet | Cost Volume Pyramid Based Depth Inference for Multi-View Stereo| CVPR 2020 | [paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Cost_Volume_Pyramid_Based_Depth_Inference_for_Multi-View_Stereo_CVPR_2020_paper.pdf)<br>[code](https://github.com/JiayuYANG/CVP-MVSNet) | ★★★★☆ |
| 6 | AA-RMVSNet | AA-RMVSNet: Adaptive Aggregation Recurrent Multi-view Stereo Network | ICCV 2021 | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wei_AA-RMVSNet_Adaptive_Aggregation_Recurrent_Multi-View_Stereo_Network_ICCV_2021_paper.pdf) <br>[Supp.](https://openaccess.thecvf.com/content/ICCV2021/supplemental/Wei_AA-RMVSNet_Adaptive_Aggregation_ICCV_2021_supplemental.pdf)<br>[Code](https://github.com/QT-Zhu/AA-RMVSNet)| ★★★ |  
| 7 | PatchmatchNet | PatchmatchNet: Learned Multi-View Patchmatch Stereo | CVPR 2021 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_PatchmatchNet_Learned_Multi-View_Patchmatch_Stereo_CVPR_2021_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Wang_PatchmatchNet_Learned_Multi-View_CVPR_2021_supplemental.pdf)<br>[Code](https://github.com/FangjinhuaWang/PatchmatchNet)| ★★☆ |  
| 8 | IterMVS | IterMVS: Iterative Probability Estimation for Efficient Multi-View Stereo | CVPR 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_IterMVS_Iterative_Probability_Estimation_for_Efficient_Multi-View_Stereo_CVPR_2022_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Wang_IterMVS_Iterative_Probability_CVPR_2022_supplemental.pdf)<br>[Code](https://github.com/FangjinhuaWang/IterMVS)| ★★★☆ |   
| 9 | TransMVSNet | TransMVSNet: Global Context-aware Multi-View Stereo Network with Transformers | CVPR 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ding_TransMVSNet_Global_Context-Aware_Multi-View_Stereo_Network_With_Transformers_CVPR_2022_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Ding_TransMVSNet_Global_Context-Aware_CVPR_2022_supplemental.pdf)<br>[Code](https://github.com/megvii-research/TransMVSNet)|  ★★★ |  
| 10 | UniMVSNet | Rethinking Depth Estimation for Multi-View Stereo: A Unified Representation and Focal Loss | CVPR 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Peng_Rethinking_Depth_Estimation_for_Multi-View_Stereo_A_Unified_Representation_CVPR_2022_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Peng_Rethinking_Depth_Estimation_CVPR_2022_supplemental.pdf)<br>[Code](https://github.com/prstrive/UniMVSNet)| ★★★★★ |  
| 11 | GBiNet | Generalized Binary Search Network for Highly-Efficient Multi-View Stereo | CVPR 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Mi_Generalized_Binary_Search_Network_for_Highly-Efficient_Multi-View_Stereo_CVPR_2022_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Mi_Generalized_Binary_Search_CVPR_2022_supplemental.pdf)<br>[Code](https://github.com/MiZhenxing/GBi-Net)|  ★★★★★ |  
| 12 | EffiMVS | Efficient Multi-view Stereo by Iterative Dynamic Cost Volume | CVPR 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Efficient_Multi-View_Stereo_by_Iterative_Dynamic_Cost_Volume_CVPR_2022_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2022/supplemental/Wang_Efficient_Multi-View_Stereo_CVPR_2022_supplemental.pdf)<br>[Code](https://github.com/bdwsq1996/Effi-MVS)|  ★★★☆ |  
| 13 | MVSTER | MVSTER: Epipolar Transformer for Efficient Multi-View Stereo | ECCV 2022 | [Paper](https://arxiv.org/pdf/2204.07346.pdf)<br>[Code](https://github.com/JeffWang987/MVSTER)|  ★★ |  
| 14 | MVSFormer | MVSFormer: Multi-View Stereo with Pre-trained Vision Transformers and Temperature-based Depth | TMLR 2023 | [Paper](https://openreview.net/pdf?id=2VWR6JfwNo)<br>[Code](https://github.com/ewrfcas/MVSFormer)|  ★★★☆ |  
| 15 | IGEV-MVS | iterative geometry encoding volume for stereo matching | CVPR 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_Iterative_Geometry_Encoding_Volume_for_Stereo_Matching_CVPR_2023_paper.pdf)<br>[Code](https://github.com/gangweiX/IGEV/tree/main/IGEV-MVS)| ★★ |  
| 16 | GeoMVSNet | GeoMVSNet: Learning Multi-View Stereo with Geometry Perception | CVPR 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_GeoMVSNet_Learning_Multi-View_Stereo_With_Geometry_Perception_CVPR_2023_paper.pdf)<br>[Supp.](https://openaccess.thecvf.com/content/CVPR2023/supplemental/Zhang_GeoMVSNet_Learning_Multi-View_CVPR_2023_supplemental.pdf)<br>[Code](https://github.com/doubleZ0108/GeoMVSNet)| ★★★★☆ |  


