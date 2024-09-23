# Awesome Learning-based Point Cloud Compression
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Report Error](https://img.shields.io/badge/🐛-Report_Error-yellow.svg?style=flat)](https://github.com/vettelx/Awesome-Learning-based-Point-Cloud-Compression/issues)
[![Pull Request](https://img.shields.io/badge/👐-Pull_Request-brightgreen.svg?style=flat)](https://github.com/vettelx/Awesome-Learning-based-Point-Cloud-Compression/pulls)

A **continual** collection of papers related to Learning-based Point Cloud Compression.


# 🚀 The scope of our collection

💡 **Topic 1:** Learning-based Point Cloud Geometry/Attribute/Unified Compression methods.
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

#### Diff-PCC: Diffusion-based Neural Compression for 3D Point Clouds 
- **🧑‍🔬 Author**: Kai Liu, Kang You, Pan Gao
- **🏫 Affiliation**: Nanjing University of Aeronautics and Astronautics
- **🔗 Link**: [Code] [[arXiv:2408.10543](https://arxiv.org/abs/2408.10543)]
- **📝 Note**:
  
#### LLM-PCGC: Large Language Model-based Point Cloud Geometry Compression 
- **🧑‍🔬 Author**: Yuqi Ye, Wei Gao
- **🏫 Affiliation**: Peking University
- **🔗 Link**: [Code] [[arXiv:2408.08682](https://arxiv.org/abs/2408.08682)]
- **📝 Note**:

#### A Du-Octree based Cross-Attention Model for LiDAR Geometry Compression 
- **🧑‍🔬 Author**: Mingyue Cui, Mingjian Feng, Junhua Long, Daosong Hu, Shuai Zhao, Kai Huang
- **🏫 Affiliation**: Sun Yat-sen University
- **🔗 Link**: [Code] [[ICRA](https://ieeexplore.ieee.org/abstract/document/10610640)]
- **📝 Note**:

#### Fast Point Cloud Geometry Compression with Context-based Residual Coding and INR-based Refinement
- **🧑‍🔬 Author**: Hao Xu, Xi Zhang, Xiaolin Wu
- **🏫 Affiliation**: McMaster University, Shanghai Jiao Tong University
- **🔗 Link**: [Code] [[arXiv:2408.02966](https://arxiv.org/abs/2408.02966)]
- **📝 Note**: 🔥 (ECCV 2024)

#### BMT-PCGC: Point Cloud Geometry Compression with Bidirectional Mask Transformer Entropy Model 
- **🧑‍🔬 Author**: Monyneath Yim, Bing-Han Wu, Jui-Chiu Chiang
- **🏫 Affiliation**: National Chung Cheng University Taiwan
- **🔗 Link**: [Code] [[PCS](https://ieeexplore.ieee.org/abstract/document/10566435)]
- **📝 Note**:

#### Enhancing octree-based context models for point cloud geometry compression with attention-based child node number prediction
- **🧑‍🔬 Author**: Chang Sun, Hui Yuan, Xiaolong Mao, Xin Lu, Raouf Hamzaoui
- **🏫 Affiliation**: Shandong University, De Montfort University
- **🔗 Link**: [Code] [[IEEE SPL](https://ieeexplore.ieee.org/document/10596661)]
- **📝 Note**: 

#### Enhancing context models for point cloud geometry compression with context feature residuals and multi-loss
- **🧑‍🔬 Author**: Chang Sun, Hui Yuan, Shuai Li, Xin Lu, Raouf Hamzaoui
- **🏫 Affiliation**: Shandong University, De Montfort University
- **🔗 Link**: [Code] [[IEEE Journal on Emerging and Selected Topics in Circuits and Systems](https://ieeexplore.ieee.org/document/10440338)]
- **📝 Note**:

#### Multi-Space Point Geometry Compression With Progressive Relation-Aware Transformer
- **🧑‍🔬 Author**: Wenxiang Shen, BaoYe Zhang, Hao Xu, XiaoHan Li, Jun Wu
- **🏫 Affiliation**: Tongji University, University of Science and Technology of China, Fudan University
- **🔗 Link**: [Code] [[TMM](https://ieeexplore.ieee.org/abstract/document/10487884)]
- **📝 Note**:

#### NeRI: Implicit Neural Representation of LiDAR Point Cloud Using Range Image Sequence
- **🧑‍🔬 Author**: Ruixiang Xue, Jiaxin Li, Tong Chen, Dandan Ding, Xun Cao, Zhan Ma
- **🏫 Affiliation**: Nanjing University, Hangzhou Normal University
- **🔗 Link**: [Code] [[ICASSP 2024](https://ieeexplore.ieee.org/abstract/document/10446596)]
- **📝 Note**:

#### Surface-Constrained Progressive Feature Preserving Point Cloud Compression
- **🧑‍🔬 Author**: Baoye Zhang, Wenxiang Shen, Bin Tan, Die Hu, Jun Wu
- **🏫 Affiliation**: Tongji University, Jinggangshan University, Fudan University
- **🔗 Link**: [[Code](https://github.com/zbaoye/SurfPCC)] [[ICASSP 2024](https://ieeexplore.ieee.org/abstract/document/10447976)]
- **📝 Note**:

#### ScanPCGC: Learning-Based Lossless Point Cloud Geometry Compression using Sequential Slice Representation
- **🧑‍🔬 Author**: Jiangwei Deng, Yuhao An, Thomas H. Li, Shan Liu, Ge Li
- **🏫 Affiliation**: Peking University, Tencent America
- **🔗 Link**: [Code] [[ICASSP 2024](https://ieeexplore.ieee.org/abstract/document/10447944)]
- **📝 Note**:

#### Temporal Conditional Coding for Dynamic Point Cloud Geometry Compression
- **🧑‍🔬 Author**: Bowen Huang; Davi Lazzarotto; Touradj Ebrahimi
- **🏫 Affiliation**: Ecole Polytechnique Fed´ erale de Lausanne
- **🔗 Link**: [Code] [[ICASSP 2024](https://ieeexplore.ieee.org/abstract/document/10447562)]
- **📝 Note**:

#### When Dynamic Neural Network Meets Point Cloud Compression: Computation-Aware Variable Rate and Checkerboard Context
- **🧑‍🔬 Author**: Zhuozhen Yu, Wei Gao
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[DCC 2024](https://ieeexplore.ieee.org/abstract/document/10533785)]
- **📝 Note**:

#### Semantic-Aware Visual Decomposition for Point Cloud Geometry Compression
- **🧑‍🔬 Author**: Liang Xie, Wei Gao, Huiming Zheng, Hua Ye
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[DCC 2024](https://ieeexplore.ieee.org/abstract/document/10533835)]
- **📝 Note**:

#### Pointsoup: High-Performance and Extremely Low-Decoding-Latency Learned Geometry Codec for Large-Scale Point Cloud Scenes
- **🧑‍🔬 Author**: Kang You, Kai Liu, Li Yu, Pan Gao, Dandan Ding
- **🏫 Affiliation**: Nanjing University of Aeronautics and Astronautics, Nanjing University of Information Science and Technology, Hangzhou Normal University
- **🔗 Link**: [[Code](https://github.com/I2-Multimedia-Lab/Pointsoup)] [[arXiv:2404.13550](https://arxiv.org/abs/2404.13550)]
- **📝 Note**: 🔥 (IJCAI 2024)

#### Point Cloud Compression via Constrained Optimal Transport 
- **🧑‍🔬 Author**: Zezeng Li, Weimin Wang, Ziliang Wang, Na Lei
- **🏫 Affiliation**: Dalian University of Technology
- **🔗 Link**: [[Code](https://github.com/cognaclee/PCC-COT)] [[arXiv:2403.08236](https://arxiv.org/abs/2403.08236)]
- **📝 Note**:

#### patchDPCC: A Patchwise Deep Compression Framework for Dynamic Point Clouds
- **🧑‍🔬 Author**: Zirui Pan, Mengbai Xiao, Xu Han, Dongxiao Yu, Guanghui Zhang, Yao Liu
- **🏫 Affiliation**: Shandong University, Rutgers University
- **🔗 Link**: [Code] [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28238)]
- **📝 Note**: AAAI 2024 [[appendix](https://github.com/pzrsdu/patchDPCC)]

#### PIVOT-Net: Heterogeneous Point-Voxel-Tree-based Framework for Point Cloud Compression 
- **🧑‍🔬 Author**: Jiahao Pang, Kevin Bui, Dong Tian
- **🏫 Affiliation**: InterDigital
- **🔗 Link**: [Code] [[3DV](https://ieeexplore.ieee.org/abstract/document/10550634)]
- **📝 Note**: 2024 International Conference on 3D Vision (3DV)

#### Deep Learning-based Point Cloud Geometry Coding with Attention Models 
- **🧑‍🔬 Author**: Mohammadreza Ghafari, André F. R. Guarda, Nuno M. M. Rodrigues, Fernando Pereira
- **🏫 Affiliation**: 
- **🔗 Link**: [Code] [[ISM](https://ieeexplore.ieee.org/abstract/document/10473490)]
- **📝 Note**: 2023 IEEE International Symposium on Multimedia (ISM)

#### Octree-Based Temporal-Spatial Context Entropy Model for LiDAR Point Cloud Compression 
- **🧑‍🔬 Author**: Longhua Sun, Jin Wang, Yunhui Shi, Qing Zhu, Baocai Yin, Nam Ling
- **🏫 Affiliation**: Beijing University of Technology, Santa Clara University
- **🔗 Link**: [Code] [[VCIP](https://ieeexplore.ieee.org/abstract/document/10402785)]
- **📝 Note**: 29 January 2024

#### OctPCGC-Net: Learning Octree-Structured Context Entropy Model for Point Cloud Geometry Compression 
- **🧑‍🔬 Author**: Xinjie Wang, Hanyun Wang, Ke Xu, Jianwei Wan, Yulan Guo
- **🏫 Affiliation**: 
- **🔗 Link**: [Code] [[PRCV](https://dl.acm.org/doi/abs/10.1007/978-981-99-8432-9_28)]
- **📝 Note**: 24 December 2023
  
#### Sparse Representation based Deep Residual Geometry Compression Network for Large-scale Point Clouds 
- **🧑‍🔬 Author**: Pengpeng Yu, Dian Zuo, Yueer Huang, Ruishan Huang, Hanyun Wang, Yulan Guo, Fan Liang
- **🏫 Affiliation**: Sun Yat-sen University, Information Engineering University, Peng Cheng Laboratory
- **🔗 Link**: [[Code](https://github.com/pengpeng-yu/FastPCC)] [[ICME](https://ieeexplore.ieee.org/document/10220062)]
- **📝 Note**: 25 August 2023 (FastPCC)

#### Efficient Hierarchical Entropy Model for Learned Point Cloud Compression 
- **🧑‍🔬 Author**: Rui Song, Chunyang Fu, Shan Liu, Ge Li
- **🏫 Affiliation**: Peking University, Tencent America
- **🔗 Link**: [Code] [[CVPR](https://ieeexplore.ieee.org/document/10205051)]
- **📝 Note**: 22 August 2023

#### Sparse Tensor-Based Multiscale Representation for Point Cloud Geometry Compression
- **🧑‍🔬 Author**: Jianqiang Wang, Dandan Ding, Zhu Li, Xiaoxing Feng, Chuntong Cao, Zhan Ma
- **🏫 Affiliation**: Nanjing University, HangZhou Normal University, University of Missouri, Jiangsu Longyuan Zhenhua Marine Engineering Co., LTD.
- **🔗 Link**: [Code] [[TPAMI](https://ieeexplore.ieee.org/document/9968173)]
- **📝 Note**: 🔥 SparsePCGC (01 December 2022)

#### 3QNet: 3D Point Cloud Geometry Quantization Compression Network 
- **🧑‍🔬 Author**: Tianxin Huang, Jiangning Zhang, Jun Chen, Zhonggan Ding, Ying Tai, Zhenyu Zhang, Chengjie Wang, Yong Liu
- **🏫 Affiliation**: Zhejiang University, Tencent youtu Lab, 
- **🔗 Link**: [[Code](https://github.com/APRIL-ZJU/3QNet)] [[ToG](https://dl.acm.org/doi/abs/10.1145/3550454.3555481)]
- **📝 Note**: 30 November 2022

#### Density-preserving Deep Point Cloud Compression 
- **🧑‍🔬 Author**: Yun He, Xinlin Ren, Danhang Tang, Yinda Zhang, Xiangyang Xue, Yanwei Fu
- **🏫 Affiliation**: Beijing University of Technology, Santa Clara University
- **🔗 Link**: [[Code](https://github.com/yunhe20/D-PCC)] [[arXiv:2204.12684](https://arxiv.org/abs/2204.12684)]
- **📝 Note**: CVPR 2022

#### OctAttention: Octree-Based Large-Scale Contexts Model for Point Cloud Compression
- **🧑‍🔬 Author**: Chunyang Fu, Ge Li, Rui Song, Wei Gao, Shan Liu
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory, Tencent America
- **🔗 Link**: [[Code](https://github.com/zb12138/OctAttention)] [[arXiv:2202.06028](https://arxiv.org/abs/2202.06028)]
- **📝 Note**: AAAI 2022

#### VoxelContext-Net: An Octree based Framework for Point Cloud Compression
- **🧑‍🔬 Author**: Zizheng Que, Guo Lu, Dong Xu
- **🏫 Affiliation**: Beihang University, Beijing Institute of Technology, University of Sydney
- **🔗 Link**: [Code] [[CVPR](https://ieeexplore.ieee.org/document/9578231)]
- **📝 Note**: CVPR 2021

#### OctSqueeze: Octree-Structured Entropy Model for LiDAR Compression
- **🧑‍🔬 Author**: Lila Huang, Shenlong Wang, Kelvin Wong, Jerry Liu, Raquel Urtasun
- **🏫 Affiliation**: Uber Advanced Technologies Group, University of Waterloo, University of Toronto
- **🔗 Link**: [Code] [[CVPR](https://ieeexplore.ieee.org/document/9157381/)]
- **📝 Note**: CVPR 2020

#### MuSCLE: Multi Sweep Compression of LiDAR using Deep Entropy Models
- **🧑‍🔬 Author**: Sourav Biswas, Jerry Liu, Kelvin Wong, Shenlong Wang, Raquel Urtasun
- **🏫 Affiliation**: Uber Advanced Technologies Group 2University of Waterloo 3University of Toronto
- **🔗 Link**: [Code] [[arXiv:2011.07590](https://arxiv.org/abs/2011.07590)]
- **📝 Note**: NeurIPS 2020

## Attribute
#### End-to-end learned Lossy Dynamic Point Cloud Attribute Compression 
- **🧑‍🔬 Author**: Dat Thanh Nguyen, Daniel Zieger, Marc Stamminger, Andre Kaup
- **🏫 Affiliation**: Chair of Multimedia Communications and Signal Processing, Chair of Visual Computing FAU
- **🔗 Link**: [Code] [[ICIP](https://arxiv.org/abs/2408.10665)]
- **📝 Note**: dynamic attribute

#### PCAC-GAN: A Sparse-Tensor-Based Generative Adversarial Network for 3D Point Cloud Attribute Compression 
- **🧑‍🔬 Author**: Xiaolong Mao, Hui Yuan, Xin Lu, Raouf Hamzaoui, Wei Gao
- **🏫 Affiliation**: 
- **🔗 Link**: [Code] [[arXiv:2407.05677](https://arxiv.org/abs/2407.05677)]
- **📝 Note**: Computational Visual Media, 2024

#### TSC-PCAC: Voxel Transformer and Sparse Convolution Based Point Cloud Attribute Compression for 3D Broadcasting
- **🧑‍🔬 Author**: Zixi Guo, Yun Zhang, Linwei Zhu, Hanli Wang, Gangyi Jiang
- **🏫 Affiliation**: Sun Yat-Sen University, Shenzhen Institute of Advanced Technology, Tongji University, Ningbo University
- **🔗 Link**: [[Code](https://github.com/igizuxo/TSC-PCAC)] [[arXiv:2407.04284](https://arxiv.org/abs/2407.04284)]
- **📝 Note**: 

#### Efficient and Generic Point Model for Lossless Point Cloud Attribute Compression
- **🧑‍🔬 Author**: Kang You, Pan Gao, Zhan Ma
- **🏫 Affiliation**: Nanjing University of Aeronautics and Astronautics, Nanjing University
- **🔗 Link**: [[Code](https://github.com/I2-Multimedia-Lab/PoLoPCAC)] [[arXiv:2404.06936](https://arxiv.org/abs/2404.06936)]
- **📝 Note**:  

#### Efficient Point Cloud Attribute Compression Using Rich Parallelizable Context Model 
- **🧑‍🔬 Author**: Ruishan Huang, Pengpeng Yu, Shaolin Liao, Fan Liang
- **🏫 Affiliation**: Sun Yat-sen University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[ICASSP 2024](https://ieeexplore.ieee.org/abstract/document/10448389)]
- **📝 Note**:

#### Embedded Coding of Point Cloud Attributes 
- **🧑‍🔬 Author**: Victor F. Figueiredo, Ricardo L. de Queiroz, Philip A. Cho, Lucas S. Lopes
- **🏫 Affiliation**: University of Brasilia, Google
- **🔗 Link**: [Code] [[IEEE ](https://ieeexplore.ieee.org/abstract/document/10474112)]
- **📝 Note**:

#### Reducing the Complexity of Normalizing Flow Architectures for Point Cloud Attribute Compression
- **🧑‍🔬 Author**: Rodrigo B. Pinheiro, Jean-Eudes Marvie, Giuseppe Valenzise, Frédéric Dufaux
- **🏫 Affiliation**: InterDigital, Inc., Universite Paris-Saclay
- **🔗 Link**: [Code] [[ICASSP](https://ieeexplore.ieee.org/abstract/document/10446754)]
- **📝 Note**:

#### Progressive Coding for Deep Learning based Point Cloud Attribute Compression
- **🧑‍🔬 Author**: Michael Rudolph, Aron Riemenschneider, Amr Rizk
- **🏫 Affiliation**: University of Duisburg-Essen
- **🔗 Link**: [[Code](https://github.com/mic-rud/ProgressivePCAC)] [[MMVE](https://dl.acm.org/doi/10.1145/3652212.3652217)]
- **📝 Note**: 15 April 2024

#### Scalable Point Cloud Attribute Compression
- **🧑‍🔬 Author**: Junteng Zhang, Jianqiang Wang, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University, Nanjing University
- **🔗 Link**: [Code] [[TMM](https://ieeexplore.ieee.org/document/10313579)]
- **📝 Note**: 09 November 2023

#### 3DAC: Learning Attribute Compression for Point Cloud
- **🧑‍🔬 Author**: Guangchi Fang, Qingyong Hu, Hanyun Wang, Yiling Xu, Yulan Guo
- **🏫 Affiliation**: Sun Yat-sen University, University of Oxford. Information Engineering University, Shanghai Jiaotong University, National University of Defense Technology
- **🔗 Link**: [[Code](https://github.com/fatPeter/ThreeDAC)] [[CVPR](https://ieeexplore.ieee.org/document/9879523)]
- **📝 Note**: 27 September 2022 (CVPR 2022)

#### SparsePCAC: Sparse Tensor-based Point Cloud Attribute Compression
- **🧑‍🔬 Author**: Jianqiang Wang, Zhan Ma
- **🏫 Affiliation**: Nanjing University
- **🔗 Link**: [[Code](https://github.com/NJUVISION/SparsePCAC)] [[MIPR](https://ieeexplore.ieee.org/abstract/document/9874468)]
- **📝 Note**: 08 Sep 2022, 2022 IEEE 5th International Conference on Multimedia Information Processing and Retrieval (MIPR)

#### Deep-PCAC: An End-to-End Deep Lossy Compression Framework for Point Cloud Attributes
- **🧑‍🔬 Author**: Xihua Sheng, Li Li, Dong Liu, Zhiwei Xiong, Zhu Li, Feng Wu
- **🏫 Affiliation**: University of Science and Technology of China, University of Missouri-Kansas City
- **🔗 Link**: [[Code](https://github.com/xhsheng-ustc/Deep-PCAC)] [[TMM](https://ieeexplore.ieee.org/document/9447226)]
- **📝 Note**: 04 June 2021

#### Folding-Based Compression Of Point Cloud Attributes
- **🧑‍🔬 Author**: Maurice Quach, Giuseppe Valenzise, Frederic Dufaux
- **🏫 Affiliation**: Université Paris-Saclay
- **🔗 Link**: [[Code](https://github.com/mauriceqch/pcc_attr_folding)] [[ICIP](https://ieeexplore.ieee.org/document/9191180)]
- **📝 Note**: ICIP 2020

## Unified
#### The JPEG Pleno Learning-based Point Cloud Coding Standard: Serving Man and Machine
- **🧑‍🔬 Author**: André F. R. Guarda, Nuno M. M. Rodrigues, Fernando Pereira
- **🏫 Affiliation**: Instituto de Telecomunicações, Lisbon, Portugal, ESTG, Politécnico de Leiria, Leiria, Portugal, Instituto Superior Técnico - Universidade de Lisboa, Lisbon, Portugal
- **🔗 Link**: [Code] [[arXiv:2409.08130](https://arxiv.org/abs/2409.08130)]
- **📝 Note**: 🔥JPEG Standard

#### Learned Compression of Point Cloud Geometry and Attributes in a Single Model through Multimodal Rate-Control
- **🧑‍🔬 Author**: Michael Rudolph, Aron Riemenschneider, Amr Rizk
- **🏫 Affiliation**: University of Duisburg-Essen,  Leibniz University Hannover
- **🔗 Link**: [Code] [[arXiv:2408.00599](https://arxiv.org/abs/2408.00599)]
- **📝 Note**:

#### Bits-to-Photon: End-to-End Learned Scalable Point Cloud Compression for Direct Rendering
- **🧑‍🔬 Author**: Yueyu Hu, Ran Gong, Yao Wang
- **🏫 Affiliation**: New York University, Tsinghua University
- **🔗 Link**: [Code] [[arXiv:2406.05915](https://arxiv.org/abs/2406.05915)]
- **📝 Note**:

#### Point Cloud Compression with Implicit Neural Representations: A Unified Framework
- **🧑‍🔬 Author**: Hongning Ruan, Yulin Shao, Qianqian Yang, Liang Zhao, Dusit Niyato
- **🏫 Affiliation**: Zhejiang University, University of Macau, Nanyang Technological University
- **🔗 Link**: [Code] [[arXiv:2405.11493](https://arxiv.org/abs/2405.11493)]
- **📝 Note**: 🔥 INR-based

#### YOGA: Yet Another Geometry-based Point Cloud Compressor
- **🧑‍🔬 Author**: Junteng Zhang, Tong Chen, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University, Nanjing University
- **🔗 Link**: [Code] [[MM](https://dl.acm.org/doi/10.1145/3581783.3613847)]
- **📝 Note**: 27 October 2023 [[website](https://3dpcc.github.io/publication/YOGAv1/)]

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
- **🔗 Link**: [Code] [[VCIP](https://ieeexplore.ieee.org/abstract/document/10402718)]
- **📝 Note**:

#### DANet: Density-Adaptive Network for Geometry-based Point Cloud Compression Artifacts Removal
- **🧑‍🔬 Author**: Zetao Yang; Wei Gao; Xijing Lu
- **🏫 Affiliation**: Peking Unviersity
- **🔗 Link**: [Code] [[VCIP](https://ieeexplore.ieee.org/abstract/document/10402662)]
- **📝 Note**:

#### TDRNet: Transformer-Based Dual-Branch Restoration Network for Geometry Based Point Cloud Compression Artifacts
- **🧑‍🔬 Author**: Xiaoyu Zhang; Guibiao Liao; Wei Gao; Ge Li
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[ICME](https://ieeexplore.ieee.org/document/9859853)]
- **📝 Note**:

#### Deep Geometry Post-Processing for Decompressed Point Clouds
- **🧑‍🔬 Author**: Xiaoqing Fan, Ge Li, Dingquan Li, Yurui Ren, Wei Gao, Thomas H. Li
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [[Code](https://github.com/fxqzb/Deep-Geometry-Post-Processing)] [[ICME](https://ieeexplore.ieee.org/document/9859723)]
- **📝 Note**:

#### Point Cloud Geometry Prediction Across Spatial Scale using Deep Learning
- **🧑‍🔬 Author**: Anique Akhtar, Wen Gao, Xiang Zhang, Li Li, Zhu Li, Shan Liu
- **🏫 Affiliation**: University of Missouri-Kansas City, Tencent
- **🔗 Link**: [Code] [[VCIP](https://ieeexplore.ieee.org/document/9301804)]
- **📝 Note**:
 

## Attribute

#### Dependence-Based Coarse-to-Fine Approach for Reducing Distortion Accumulation in G-PCC Attribute Compression
- **🧑‍🔬 Author**: Tian Guo, Hui Yuan, Raouf Hamzaoui, Xiaohui Wang, Lu Wang
- **🏫 Affiliation**: Shandong University, De Montfort University
- **🔗 Link**: [Code] [[ IEEE Transactions on Industrial Informatics](https://ieeexplore.ieee.org/abstract/document/10549850)]
- **📝 Note**: traditional method

#### Fast Inter-frame Motion Prediction for Compressed Dynamic Point Cloud Attribute Enhancement
- **🧑‍🔬 Author**: Wang Liu, Wei Gao, Xingming Mu
- **🏫 Affiliation**: Peking University, Peng Cheng Laboratory
- **🔗 Link**: [Code] [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28162)]
- **📝 Note**: **Dynamic** Attribute Enhancement

#### A Small-Scale Image U-Net-Based Color Quality Enhancement for Dense Point Cloud
- **🧑‍🔬 Author**: Jinrui Xing, Hui Yuan, Wei Zhang, Tian Guo, Chen Chen
- **🏫 Affiliation**: Shandong University, Xidian University
- **🔗 Link**: [[Code](https://github.com/xjr998/SSIU)] [[IEEE Transactions on Consumer Electronics](https://ieeexplore.ieee.org/abstract/document/10445207)]
- **📝 Note**:

#### MUSCON: Multi-scale Sparse Conv Learning for Point Cloud Attributes Deblocking
- **🧑‍🔬 Author**: Muhammad Talha, Birendra Kathariya, Zhu Li, Geert Van Der Auwera
- **🏫 Affiliation**: University Of Missouri-Kansas City, Qualcomm Technologies
- **🔗 Link**: [Code] [[DCC 2024](https://ieeexplore.ieee.org/abstract/document/10533833)]
- **📝 Note**: 

#### Fast Graph-Based Denoising For Point Cloud Color Information
- **🧑‍🔬 Author**: Ryosuke Watanabe; Keisuke Nonaka; Eduardo Pavez; Tatsuya Kobayashi; Antonio Ortega
- **🏫 Affiliation**: University of Southern California, ‡ KDDI Research, Inc.
- **🔗 Link**: [Code] [[ICASSP](https://ieeexplore.ieee.org/abstract/document/10446200)]
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
- **🔗 Link**: [Code] [[ICASSP](https://ieeexplore.ieee.org/abstract/document/10095488)]
- **📝 Note**: traditional method, graph-based

#### Wiener Filter-based Color Attribute Quality Enhancement for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Jinrui Xing, Hui Yuan, Chen Chen, Wei Gao
- **🏫 Affiliation**: Shandong University, Peking University
- **🔗 Link**: [Code] [[APSIPAASC](https://ieeexplore.ieee.org/document/9979990)]
- **📝 Note**: traditional method

#### Attribute Artifacts Removal for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Xihua Sheng; Li Li; Dong Liu; Zhiwei Xiong
- **🏫 Affiliation**: University of Science and Technology of China
- **🔗 Link**: [[Code](https://github.com/xhsheng-ustc/MS-GAT)] [[TIP](https://ieeexplore.ieee.org/document/9767661)]
- **📝 Note**: MS-GAT
  
## Unified
#### GPCC++: Enhanced Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Junzhe Zhang, Tong Chen, Dandan Ding, and Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [Code] [[ACM MM](https://dl.acm.org/doi/abs/10.1145/3581783.3613827)]
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

#### Scalable Human-Machine Point Cloud Compression
- **🧑‍🔬 Author**: Mateen Ulhaq, Ivan V. Bajić
- **🏫 Affiliation**: Simon Fraser University
- **🔗 Link**: [Code] [[arXiv:2402.12532](https://arxiv.org/abs/2402.12532)]
- **📝 Note**: 2024 PCS

#### Learned Point Cloud Compression for Classification
- **🧑‍🔬 Author**: Mateen Ulhaq, Ivan V. Bajić
- **🏫 Affiliation**: Simon Fraser University
- **🔗 Link**: [[Code](https://github.com/multimedialabsfu/learned-point-cloud-compression-for-classification
)] [[arXiv:2308.05959](https://arxiv.org/abs/2308.05959)]
- **📝 Note**: IEEE MMSP 2023

# 💡 Quality Assessment / Rate Control
## Quality Assessment
#### No-reference Bitstream-based Perceptual Quality Assessment of Octree-Lifting Encoded 3D Point Clouds
- **🧑‍🔬 Author**: Jianyu Lv, Honglei Su, Qi Liu, Hui Yuan
- **🏫 Affiliation**: Shenzhen Institutes of Advanced Technology,  Sun Yat-sen University, Shenzhen Polytechnic University, DeMonfort University
- **🔗 Link**: [Code] [[TVCG](https://ieeexplore.ieee.org/abstract/document/10637704)]
- **📝 Note**:

#### Colored Point Cloud Quality Assessment Using Complementary Features in 3D and 2D Spaces
- **🧑‍🔬 Author**: Mao Cui, Yun Zhang, Chunling Fan, Raouf Hamzaoui, Qinglan Li
- **🏫 Affiliation**: Qingdao University,  Shandong University
- **🔗 Link**: [Code] [[TMM](https://ieeexplore.ieee.org/abstract/document/10637704)]
- **📝 Note**:

#### 3DTA: No-Reference 3D Point Cloud Quality Assessment with Twin Attention
- **🧑‍🔬 Author**: Linxia Zhu, Jun Cheng, Xu Wang, Honglei Su, Huan Yang, Hui Yuan, Jari Korhonen
- **🏫 Affiliation**: Qingdao University, BYD Auto Industry Co., Ltd., Shenzhen University, Shandong University, University of
Aberdeen
- **🔗 Link**: [Code] [[TMM](https://ieeexplore.ieee.org/abstract/document/10542438)]
- **📝 Note**:

#### Zoom to Perceive Better: No-Reference Point Cloud Quality Assessment via Exploring Effective Multiscale Feature
- **🧑‍🔬 Author**: Jilong Wang, Wei Gao, Ge Li
- **🏫 Affiliation**:  Peng Cheng Laboratory, Peking University 
- **🔗 Link**: [Code] [[TCSVT](https://ieeexplore.ieee.org/abstract/document/10422856)]
- **📝 Note**:
  
## Rate Control
#### Content-aware Rate Control for Geometry-based Point Cloud Compression
- **🧑‍🔬 Author**: Junteng Zhang, Junzhe Zhang, Wenxi Ma, Dandan Ding, Zhan Ma
- **🏫 Affiliation**: Hangzhou Normal University,  Nanjing University
- **🔗 Link**: [Code] [[TCSVT](https://ieeexplore.ieee.org/abstract/document/10530090)]
- **📝 Note**:
  
#### Rate Control Optimization for Joint Geometry and Attribute Coding of LiDAR Point Clouds
- **🧑‍🔬 Author**: Yang Wang, Wei Gao, Xingming Mu, Hang Yuan
- **🏫 Affiliation**: Peking University 
- **🔗 Link**: [Code] [[VCIP](https://ieeexplore.ieee.org/abstract/document/10402779)]
- **📝 Note**:

#### Rate-Distortion Modeling for Bit Rate Constrained Point Cloud Compression
- **🧑‍🔬 Author**: Pan Gao, Shengzhou Luo, Manoranjan Paul
- **🏫 Affiliation**: Nanjing University of Aeronautics and Astronautics, South China Normal University, Charles Sturt University
- **🔗 Link**: [Code] [[TCSVT](https://ieeexplore.ieee.org/document/9957096)]
- **📝 Note**:
  
# 💡 Point Cloud Analysis methods
#### Point Mamba: A Novel Point Cloud Backbone Based on State Space Model with Octree-Based Ordering Strategy
- **🧑‍🔬 Author**:  Jiuming Liu, Ruiji Yu, Yian Wang, Yu Zheng, Tianchen Deng, Weicai Ye, Hesheng Wang
- **🏫 Affiliation**: Shanghai Jiao Tong University, Zhejiang University
- **🔗 Link**: [[Code](https://github.com/IRMVLab/Point-Mamba)] [[arXiv:2403.06467](https://arxiv.org/abs/2403.06467v2)]
- **📝 Note**:

#### Dynamic Graph CNN for Learning on Point Clouds
- **🧑‍🔬 Author**:  Yue Wang, Yongbin Sun, Ziwei Liu, Sanjay E. Sarma, Michael M. Bronstein, Justin M. Solomon
- **🏫 Affiliation**: Massachusetts Institute of Technology, UC Berkeley/ICSI, Imperial College London/USI Lugano
- **🔗 Link**: [[Code](https://github.com/WangYueFt/dgcnn)] [[TOG](https://dl.acm.org/doi/10.1145/3326362)]
- **📝 Note**: DGCNN, 10 October 2019

### 👍 Acknowledgement
Thanks to the [Awesome-T2I-safety-Papers](https://github.com/SaFoLab-WISC/Awesome-T2I-safety-Papers).
