# Awesome-Learning-based-Point-Cloud-Compression
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Update Log](https://img.shields.io/badge/💡-Update_Log-informational.svg?style=flat)](README.md)
[![Report Error](https://img.shields.io/badge/🐛-Report_Error-yellow.svg?style=flat)](https://github.com/vettelx/Awesome-Learning-based-Point-Cloud-Compression/issues)
[![Pull Request](https://img.shields.io/badge/👐-Pull_Request-brightgreen.svg?style=flat)](https://github.com/vettelx/Awesome-Learning-based-Point-Cloud-Compression/pulls)

A **continual** collection of papers related to Learning-based Point Cloud Compression.


# 🚀 The scope of our collection

💡 **Topic 1:** Learning-based Lossless/Lossy Point Cloud Geometry/Attribute/Integrated Compression methods.
> 
💡 **Topic 2:** Post-processing / Quality Enhancement / Artifact Removal of Compressed Point Clouds.
>
💡 **Topic 3:** Point Cloud Compression for Machine. 
>
💡 **Topic 4:** Rate Control / Quality Assessment of Point Clouds. 
> 
💡 **Topic 5:** Point Cloud Analysis methods
> This topic mainly contains articles focusing on point cloud analysis tasks, but the network structure can be used as a backbone in point cloud compression tasks, or the ideas can be borrowed by point cloud compression tasks.
  
---
# 💡 Compression

## Geometry
#### LLM-PCGC: Large Language Model-based Point Cloud Geometry Compression 
- **🧑‍🔬 Author**: Yuqi Ye, Wei Gao
- **🏫 Affiliation**: Peking University
- **🔗 Link**: [Code] [[arXiv:2408.08682](https://arxiv.org/abs/2408.08682)]
- **📝 Note**: 

## Attribute
#### [1] MMA-Diffusion: MultiModal Attack on Diffusion Models
- **🧑‍🔬 Author**: Yijun Yang, Ruiyuan Gao, Xiaosen Wang, Tsung-Yi Ho, Nan Xu, Qiang Xu
- **🏫 Affiliation**: The Chinese University of Hong Kong, Huawei Singular Security Lab, Institute of Automation, Chinese Academy of Sciences, Beijing Wenge Technology Co. Ltd
- **🔗 Link**: [[Code](https://github.com/cure-lab/MMA-Diffusion)] [[arXiv:2311.17516](https://arxiv.org/abs/2311.17516)]
- **📝 Note**: 🔥 (CVPR2024)

## Integrated
#### Learned Compression of Point Cloud Geometry and Attributes in a Single Model through Multimodal Rate-Control
- **🧑‍🔬 Author**: Michael Rudolph, Aron Riemenschneider, Amr Rizk
- **🏫 Affiliation**: University of Duisburg-Essen,  Leibniz University Hannover
- **🔗 Link**: [Code] [[arXiv:2408.00599](https://arxiv.org/abs/2408.00599)]
- **📝 Note**: 

# 💡 Quality Enhancement
## Geometry
#### Encoding Auxiliary Information to Restore Compressed Point Cloud Geometry
- **🧑‍🔬 Author**: Gexin Liu, Jiahao Zhu, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [Code] [[IJCAI](https://www.ijcai.org/proceedings/2024/0242.pdf)]
- **📝 Note**:

#### GRNet: Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling
- **🧑‍🔬 Author**: Gexin Liu, Ruixiang Xue, Jiaxin Li, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [[Code](https://github.com/3dpcc/GRNet)] [[TVCG](https://ieeexplore.ieee.org/document/10328911)]
- **📝 Note**:

#### Density-aware Swin Transformer for Compressed Point Cloud Geometry Artifacts Removal
- **🧑‍🔬 Author**: Xiqian Yu, Xin Li, Hanxin Zhu, Zhibo Chen
- **🏫 Affiliation**: Unviersity of Science and Technology of China
- **🔗 Link**: [[Code]] [[VCIP](https://ieeexplore.ieee.org/abstract/document/10402718)]
- **📝 Note**:

#### Deep Geometry Post-Processing for Decompressed Point Clouds
- **🧑‍🔬 Author**: Xiaoqing Fan, Ge Li, Dingquan Li, Yurui Ren, Wei Gao, Thomas H. Li
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [[Code](https://github.com/fxqzb/Deep-Geometry-Post-Processing)] [[ICME](https://ieeexplore.ieee.org/document/9859723)]
- **📝 Note**:

#### Point Cloud Geometry Prediction Across Spatial Scale using Deep Learning
- **🧑‍🔬 Author**: Anique Akhtar, Wen Gao, Xiang Zhang, Li Li, Zhu Li, Shan Liu
- **🏫 Affiliation**: University of Missouri-Kansas City, Tencent
- **🔗 Link**: [[Code]] [[VCIP](https://ieeexplore.ieee.org/document/9301804)]
- **📝 Note**:
 

## Attribute

#### Dependence-Based Coarse-to-Fine Approach for Reducing Distortion Accumulation in G-PCC Attribute Compression
- **🧑‍🔬 Author**: Tian Guo, Hui Yuan, Raouf Hamzaoui, Xiaohui Wang, Lu Wang
- **🏫 Affiliation**: Shandong University, De Montfort University
- **🔗 Link**: [[Code]] [[ IEEE Transactions on Industrial Informatics](https://ieeexplore.ieee.org/abstract/document/10549850)]
- **📝 Note**: traditional method

#### Fast Inter-frame Motion Prediction for Compressed Dynamic Point Cloud Attribute Enhancement
- **🧑‍🔬 Author**: Wang Liu, Wei Gao, Xingming Mu
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28162)]
- **📝 Note**: **Dynamic** Attribute Enhancement

#### A Small-Scale Image U-Net-Based Color Quality Enhancement for Dense Point Cloud
- **🧑‍🔬 Author**: Jinrui Xing; Hui Yuan; Wei Zhang; Tian Guo; Chen Chen
- **🏫 Affiliation**: Shandong University, Xidian University
- **🔗 Link**: [[Code](https://github.com/xjr998/SSIU)] [[IEEE Transactions on Consumer Electronics](https://ieeexplore.ieee.org/abstract/document/10445207)]
- **📝 Note**:

#### Fast Graph-Based Denoising For Point Cloud Color Information
- **🧑‍🔬 Author**: Ryosuke Watanabe; Keisuke Nonaka; Eduardo Pavez; Tatsuya Kobayashi; Antonio Ortega
- **🏫 Affiliation**: University of Southern California, ‡ KDDI Research, Inc.
- **🔗 Link**: [[Code]] [[ICASSP](https://ieeexplore.ieee.org/abstract/document/10446200)]
- **📝 Note**: traditonal method
  
#### Learning to Restore Compressed Point Cloud Attribute: A Fully Data-Driven Approach and A Rules-Unrolling-Based Optimization
- **🧑‍🔬 Author**: Junteng Zhang, Junzhe Zhang, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [Code] [[TVCG](https://ieeexplore.ieee.org/document/10470357)]
- **📝 Note**:

#### ARNet: Compression Artifact Reduction for Point Cloud Attribute
- **🧑‍🔬 Author**: Junzhe Zhang, Junteng Zhang, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [[Code](https://github.com/3dpcc/ARNet)] [[arXiv:2209.08276](https://arxiv.org/abs/2209.08276)]
- **📝 Note**:

#### GQE-Net: a graph-based quality enhancement network for point cloud color attribute
- **🧑‍🔬 Author**: Jinrui Xing; Hui Yuan; Raouf Hamzaoui; Hao Liu; Junhui Hou
- **🏫 Affiliation**: Shandong University, De Montfort University, Yantai University, City University of Hong Kong
- **🔗 Link**: [[Code]([https://github.com/3dpcc/ARNet](https://github.com/xjr998/GQE-Net))] [[TIP](https://ieeexplore.ieee.org/abstract/document/10314418)]
- **📝 Note**: learning-based graph-based


#### Graph-Based Point Cloud Color Denoising with 3-Dimensional Patch-Based Similarity
- **🧑‍🔬 Author**: Ryosuke Watanabe; Keisuke Nonaka; Eduardo Pavez; Tatsuya Kobayashi; Antonio Ortega
- **🏫 Affiliation**: University of Southern California, KDDI Research, Inc.
- **🔗 Link**: [[Code])] [[ICASSP](https://ieeexplore.ieee.org/abstract/document/10095488)]
- **📝 Note**: traditional method, graph-based

#### Wiener Filter-based Color Attribute Quality Enhancement for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Jinrui Xing, Hui Yuan, Chen Chen, Wei Gao
- **🏫 Affiliation**: Shandong University, Peking University
- **🔗 Link**: [[Code])] [[APSIPAASC](https://ieeexplore.ieee.org/document/9979990)]
- **📝 Note**: traditional method


#### Attribute Artifacts Removal for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Xihua Sheng; Li Li; Dong Liu; Zhiwei Xiong
- **🏫 Affiliation**: University of Science and Technology of China
- **🔗 Link**: [[Code]] [[TIP](https://ieeexplore.ieee.org/document/9767661)]
- **📝 Note**:
  

## Integrated
#### GPCC++: Enhanced Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Junzhe Zhang, Tong Chen, Dandan Ding, and Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [[Code]] [[ACM MM](https://dl.acm.org/doi/abs/10.1145/3581783.3613827)]
- **📝 Note**: [[website](https://3dpcc.github.io/publication/GPCCplusplus/)]


# 💡 PCC for Machine
#### Towards Point Cloud Compression for Machine Perception: A Simple and Strong Baseline by Learning the Octree Depth Level Predictor
- **🧑‍🔬 Author**: Lei Liu, Zhihao Hu, Zhenghao Chen
- **🏫 Affiliation**: Beihang University, School of Electrical and Information Engineering, The University of Sydney
- **🔗 Link**: [Code] [[arXiv:2406.00791](https://arxiv.org/abs/2406.00791)]
- **📝 Note**:  Scalable Coding for Machine

#### SPCGC: Scalable Point Cloud Geometry Compression for Machine Vision
- **🧑‍🔬 Author**: Liang Xie, Wei Gao, Huiming Zheng, Ge Li
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[ICRA](https://ieeexplore.ieee.org/document/10610894)]
- **📝 Note**: 

# 💡 Quality Assessment / Rate Control
## Quality Assessment
#### No-reference Bitstream-based Perceptual Quality Assessment of Octree-Lifting Encoded 3D Point Clouds
- **🧑‍🔬 Author**: Jianyu Lv, Honglei Su, Qi Liu, Hui Yuan
- **🏫 Affiliation**: Shenzhen Institutes of Advanced Technology,  Sun Yat-sen University, Shenzhen Polytechnic University, DeMonfort University
- **🔗 Link**: [Code] [[TVCG](https://ieeexplore.ieee.org/abstract/document/10637704)]
- **📝 Note**: 🔥 (TVCG)

#### Colored Point Cloud Quality Assessment Using Complementary Features in 3D and 2D Spaces
- **🧑‍🔬 Author**: Mao Cui, Yun Zhang, Chunling Fan, Raouf Hamzaoui, Qinglan Li
- **🏫 Affiliation**: Qingdao University,  Shandong University
- **🔗 Link**: [[Code]] [[TMM](https://ieeexplore.ieee.org/abstract/document/10637704)]
- **📝 Note**: 🔥 (TMM)
- 
## Rate Control
#### Content-aware Rate Control for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Junteng Zhang, Junzhe Zhang, Wenxi Ma, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [Code] [[TCSVT](https://ieeexplore.ieee.org/abstract/document/10530090)]
- **📝 Note**:

#### Rate-Distortion Modeling for Bit Rate Constrained Point Cloud Compression
- **🧑‍🔬 Author**: Pan Gao, Shengzhou Luo, Manoranjan Paul
- **🏫 Affiliation**: Nanjing University of Aeronautics and Astronautics, South China Normal University, Charles Sturt University
- **🔗 Link**: [Code] [[TCSVT](https://ieeexplore.ieee.org/document/9957096)]
- **📝 Note**:
  








  


# 💡 Point Cloud Analysis methods

#### [0] Watermark-based Detection and Attribution of AI-Generated Content
- **🧑‍🔬 Author**:  Zhengyuan Jiang, Moyang Guo, Yuepeng Hu, Neil Zhenqiang Gong
- **🏫 Affiliation**: Duke University
- **🔗 Link**: [Code] [[arXiv:2404.04254](https://arxiv.org/abs/2404.04254)]
- **📝 Note**:


### 👍 Acknowledgement
Thanks to the [Awesome-T2I-safety-Papers](https://github.com/SaFoLab-WISC/Awesome-T2I-safety-Papers).
