# Image Inpainting #
This repository is a paper list of image inpainting. Feel free to contact me (yutao666@mail.ustc.edu.cn) if you find any interesting paper about inpainting that I missed. I would greatly appreciate it : )  

If you find this repo is helpful, please cite it.
```
@techreport{Yu_A_Survey_on_2019,
author = {Yu, Tao},
month = {3},
title = {{A Survey on Image Inpainting Methods}},
year = {2019}
}
```

## Traditional Methods
Year|Proceeding|Title|Tag
--|:--:|:--:|:--:
2000|SIGGRAPH 2000|Image Inpainting  [[pdf]](http://slipguru.disi.unige.it/readinggroup/papers_vis/bertalmio00inpainting.pdf)  |Diffusion-based
2001|TIP 2001|Filling-in by joint interpolation of vector fields and gray levels [[pdf]](https://conservancy.umn.edu/bitstream/handle/11299/3462/1/1706.pdf)|Diffusion-based
2001|CVPR 2001|Navier-stokes, ﬂuid dynamics, and image and video inpainting [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=990497)|
2001|SIGGRAPH 2001|Image Quilting for Texture Synthesis and Transfer [[pdf]](https://people.eecs.berkeley.edu/~efros/research/quilting/quilting.pdf)  |
2001|SIGGRAPH 2001|Synthesizing Natural Textures [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.359.8241&rep=rep1&type=pdf)|
2002|EJAM 2002|Digital inpainting based on the mumford–shah–euler image model [[pdf]](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/26ACC4694C7F064B6F40D55C09ACA9A1/S0956792502004904a.pdf/digital_inpainting_based_on_the_mumfordshaheuler_image_model.pdf)  |Diffusion-based
2003|CVPR 2003| Object removal by exemplar-based inpainting [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1211538)|
2003|TIP 2003|Simultaneous structure and texture image inpainting [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1217265)|Diffusion-based
2003|TIP 2003|Structure and Texture Filling-In of Missing Image Blocks in Wireless Transmission and Compression Applications [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1197835)|
2003|ICCV 2003|Learning How to Inpaint from Global Image Statistics [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1238360)|Diffusion-based
2003|TOG 2003|Fragment-based image completion [[pdf]](http://delivery.acm.org/10.1145/890000/882267/p303-drori.pdf?ip=222.195.92.10&id=882267&acc=ACTIVE%20SERVICE&key=BF85BBA5741FDC6E%2EA4F9C023AC60E700%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1553430113_8d3cc7f5adde2fb3894043de791d9150) | Patch-based
2004|TIP 2004|Region Filling and Object Removal by Exemplar-Based Image Inpainting [[pdf]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/criminisi_tip2004.pdf)|Patch-based; Inpainting order
2004|TPAMI 2004|Space-Time Video Completion [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1315022) |
2005|SIGGRAPH 2005|Image Completion with Structure Propagation [[pdf]](http://jiansun.org/papers/ImageCompletion_SIGGRAPH05.pdf)|Patch-based
2006|ISCS 2006|Image Compression with Structure Aware Inpainting [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1692960)|
2007|TOG 2007| Scene completion using millions of photographs [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.299.518&rep=rep1&type=pdf)|   
2007|CSVT 2007|Image Compression With Edge-Based Inpainting [[pdf]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/inpainting_csvt_07.pdf)|Diffusion-based
2008|CVPR 2008|Summarizing Visual Data Using Bidirectional Similarity [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4587842)|
2009|SIGGRAPH 2009|PatchMatch: a randomized correspondence algorithm for structural image editing [[pdf]](http://www.faculty.idc.ac.il/arik/seminar2009/papers/patchMatch.pdf)  |Patch-based
2010| TIP 2010|Image inpainting by patch propagation using patch sparsity [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5404308) |Patch-based
2011|FTCGV 2011|Structured learning and prediction in computer vision [[pdf]](http://pub.ist.ac.at/~chl/papers/nowozin-fnt2011.pdf)|
2011|ICIP 2011|Examplar-based inpainting based on local geometry [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6116441)|Inpainting order
2012|TOG 2012|Combining inconsistent images using patch-based synthesis[[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.364.5147&rep=rep1&type=pdf)|Patch-based
2014|TOG 2014|Image completion using Planar structure guidance [[pdf]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/structure_completion_small.pdf)|Patch-based
2014|TVCG 2014|High-Quality Real-Time Video Inpainting with PixMix [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6714519)|Video
2014|SIAM 2014|Video inpainting of complex scenes [[pdf]](https://arxiv.org/pdf/1503.05528.pdf)|Video
2015|TIP 2015|Annihilating Filter-Based Low-Rank Hankel Matrix Approach for Image Inpainting [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7127011)|
2015|TIP 2015|Exemplar-Based Inpainting: Technical Review and New Heuristics for Better Geometric Reconstructions [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7056453)|
2016|TOG 2016|Temporally coherent completion of dynamic video [[pdf]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/SigAsia_2016_VideoCompletion.pdf) | Video



## Deep-learning-based Methods
Year|Proceeding|Title|Tag
--|:--:|:--:|:--
2012|NIPS 2012| Image denoising and inpainting with deep neural networks [[pdf]](http://papers.nips.cc/paper/4686-image-denoising-and-inpainting-with-deep-neural-networks.pdf)|
2014|GCPR 2014|Mask-specific inpainting with deep neural networks [[pdf]](https://link.springer.com/chapter/10.1007/978-3-319-11752-2_43)|
2014|NIPS 2014|Deep Convolutional Neural Network for Image Deconvolution [[pdf]](http://papers.nips.cc/paper/5485-deep-convolutional-neural-network-for-image-deconvolution.pdf)|
2015|NIPS 2015|Shepard Convolutional Neural Networks [[pdf]](https://papers.nips.cc/paper/5774-shepard-convolutional-neural-networks.pdf) [[code]](https://github.com/jimmy-ren/vcnn_double-bladed/tree/master/applications/Shepard_CNN)|
2016|CVPR 2016|Context Encoders: Feature Learning by Inpainting [[pdf]](https://arxiv.org/abs/1604.07379) [[code]](https://github.com/pathak22/context-encoder)|
2016|SIGGRAPH 2016|High-resolution multi-scale neural texture synthesis [[pdf]](https://wxs.ca/research/multiscale-neural-synthesis/Snelgrove-multiscale-texture-synthesis.pdf)|
2017|CVPR 2017|Semantic image inpainting with deep generative models [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf) [[code]](https://github.com/moodoki/semantic_image_inpainting)|
2017|CVPR 2017|High-resolution image inpainting using multi-scale neural patch synthesis [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_High-Resolution_Image_Inpainting_CVPR_2017_paper.pdf) [[code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)|
2017|CVPR 2017|Generative Face Completion [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf) [[code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)|
2017|SIGGRAPH 2017|Globally and Locally Consistent Image Completion [[pdf]](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/data/completion_sig2017.pdf) [[code]](https://github.com/satoshiiizuka/siggraph2017_inpainting)|
2018|CVPR 2018|Generative Image Inpainting with Contextual Attention [[pdf]](https://arxiv.org/abs/1801.07892) [[code]](https://github.com/JiahuiYu/generative_inpainting)|
2018|CVPR 2018|Natural and Effective Obfuscation by Head Inpainting [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Natural_and_Effective_CVPR_2018_paper.pdf)|
2018|CVPR 2018|Eye In-Painting With Exemplar Generative Adversarial Networks [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dolhansky_Eye_In-Painting_With_CVPR_2018_paper.pdf) [[code]](https://github.com/bdol/exemplar_gans)|
2018|CVPR 2018|UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_UV-GAN_Adversarial_Facial_CVPR_2018_paper.pdf)|
2018|CVPR 2018|Disentangling Structure and Aesthetics for Style-aware Image Completion [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)|
2018|ECCV 2018|Image Inpainting for Irregular Holes Using Partial Convolutions [[pdf]](https://arxiv.org/pdf/1804.07723.pdf) [[code]](https://github.com/NVIDIA/partialconv)|
2018|ECCV 2018| Contextual-based Image Inpainting: Infer, Match, and Translate [[pdf]](https://arxiv.org/pdf/1711.08590.pdf)|
2018|ECCV 2018|Shift-Net: Image Inpainting via Deep Feature Rearrangement [[pdf]](https://arxiv.org/pdf/1801.09392v2.pdf) [[code]](https://github.com/Zhaoyi-Yan/Shift-Net)|
2018|NIPS 2018|Image Inpainting via Generative Multi-column Convolutional Neural Networks [[pdf]](https://arxiv.org/pdf/1810.08771.pdf) [[code]](https://github.com/shepnerd/inpainting_gmcnn)|
2018|TOG 2018|Faceshop: Deep sketch-based face image editing [[pdf]](https://arxiv.org/pdf/1804.08972.pdf)|
2018|ACM MM 2018|Structural inpainting [[pdf]](https://arxiv.org/pdf/1803.10348.pdf) |
2018|ACM MM 2018|Semantic Image Inpainting with Progressive Generative Networks [[pdf]](https://dl.acm.org/citation.cfm?id=3240625) [[code]](https://github.com/crashmoon/Progressive-Generative-Networks)|
2018|BMVC 2018|SPG-Net: Segmentation Prediction and Guidance Network for Image Inpainting [[pdf]](https://arxiv.org/pdf/1805.03356.pdf)|
2018|BMVC 2018|MC-GAN: Multi-conditional Generative Adversarial Network for Image Synthesi [[pdf]](https://arxiv.org/pdf/1805.01123.pdf) [[code]](https://github.com/HYOJINPARK/MC_GAN) |
2018|ACCV 2018|Face Completion iwht Semantic Knowledge and Collaborative Adversarial Learning [[pdf]](https://arxiv.org/pdf/1812.03252.pdf)|
2018|ICASSP 2018|Edge-Aware Context Encoder for Image Inpainting [[pdf]](http://mirlab.org/conference_papers/International_Conference/ICASSP%202018/pdfs/0003156.pdf)|
2018|ICPR 2018|Deep Structured Energy-Based Image Inpainting [[pdf]](https://arxiv.org/pdf/1801.07939.pdf) [[code]](https://github.com/cvlab-tohoku/DSEBImageInpainting)|
2018|AISTATS 2019|Probabilistic Semantic Inpainting with Pixel Constrained CNNs [[pdf]](https://arxiv.org/pdf/1810.03728.pdf)|
2019|ICRA 2019| Empty Cities: Image Inpainting for a Dynamic-Object-Invariant Space [[pdf]](https://arxiv.org/pdf/1809.10239.pdf)  | 
2019|AAAI 2019|Video Inpainting by Jointly Learning Temporal Structure and Spatial Details [[pdf]](https://arxiv.org/pdf/1806.08482.pdf)| Video
2019|CVPR 2019| Pluralistic Image Completion [[pdf]](https://arxiv.org/pdf/1903.04227.pdf) [[code]](https://github.com/lyndonzheng/Pluralistic) [[project]](http://www.chuanxiaz.com/publication/pluralistic/?tdsourcetag=s_pctim_aiomsg)|
2019|CVPR 2019| Deep Reinforcement Learning of Volume-guided Progressive View Inpainting for 3D Point Scene Completion from a Single Depth Image [[pdf]](https://arxiv.org/pdf/1903.04019.pdf)|
2019|CVPR 2019|Foreground-aware Image Inpainting [[pdf]](https://arxiv.org/pdf/1901.05945.pdf)  |
2019|CVPR 2019 |Privacy Protection in Street-View Panoramas using Depth and Multi-View Imagery [[pdf]](https://arxiv.org/pdf/1903.11532.pdf) |
2019|CVPR 2019|Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting [[pdf]](https://arxiv.org/pdf/1904.07475.pdf) [[code]](https://github.com/researchmm/PEN-Net-for-Inpainting)
2019|CVPR 2019|Deep Flow-Guided Video Inpainting [[pdf]](https://arxiv.org/pdf/1905.02884.pdf) [[project]](https://nbei.github.io/video-inpainting.html)| Video
2019|CVPR 2019|Deep video inapinting [[pdf]](https://arxiv.org/pdf/1905.01639.pdf)|Video
2019|CVPRW 2019 |VORNet: Spatio-temporally Consistent Video Inpainting for Object Removal [[pdf]](https://arxiv.org/pdf/1904.06726) | Video
2019|TNNLS 2019|PEPSI++: Fast and Lightweight Network for Image Inpainting [[pdf]](https://arxiv.org/pdf/1905.09010.pdf)| 
2019|IJCAI 2019|MUSICAL: Multi-Scale Image Contextual Attention Learning for Inpainting [[pdf]](https://www.ijcai.org/proceedings/2019/0520.pdf) |
2019|IJCAI 2019|Generative Image Inpainting with Submanifold Alignment [[pdf]](https://arxiv.org/pdf/1908.00211.pdf) |
2019|ACM MM 2019| Progressive Image Inpainting with Full-Resolution Residual Network [[pdf]](https://arxiv.org/pdf/1907.10478.pdf) [[code]](https://github.com/ZongyuGuo/Inpainting_FRRN)| 
2019|ACM MM 2019| Deep Fusion Network for Image Completion [[pdf]](https://arxiv.org/pdf/1904.08060.pdf) [[code]](https://github.com/hughplay/DFNet)| 
2019|ACM MM 2019| GAIN: Gradient Augmented Inpainting Network for Irregular Holes [[pdf]](https://dl.acm.org/citation.cfm?id=3350912) |
2019|ACM MM 2019| Single-shot Semantic Image Inpainting with Densely Connected Generative Networks [[pdf]](https://dl.acm.org/citation.cfm?id=3350903) |
2019|ICCVW 2019|EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning [[pdf]](https://arxiv.org/pdf/1901.00212.pdf) [[code]](https://github.com/knazeri/edge-connect)|
2019|ICCV 2019|Coherent Semantic Attention for Image Inpainting [[pdf]](https://arxiv.org/pdf/1905.12384.pdf) [[code]](https://github.com/KumapowerLIU/CSA-inpainting)| 
2019|ICCV 2019|StructureFlow: Image Inpainting via Structure-aware Appearance Flow [[pdf]](https://arxiv.org/pdf/1908.03852.pdf) [[code]](https://github.com/RenYurui/StructureFlow) | 
2019|ICCV 2019|Progressive Reconstruction of Visual Structure for Image Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Progressive_Reconstruction_of_Visual_Structure_for_Image_Inpainting_ICCV_2019_paper.pdf) [[code]](https://github.com/jingyuanli001/PRVS-Image-Inpainting) | 
2019|ICCV 2019| Localization of Deep Inpainting Using High-Pass Fully Convolutional Network [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Localization_of_Deep_Inpainting_Using_High-Pass_Fully_Convolutional_Network_ICCV_2019_paper.pdf)|
2019|ICCV 2019| Image Inpainting with Learnable Bidirectional Attention Maps [[pdf]](https://arxiv.org/pdf/1909.00968.pdf) [[code]](https://github.com/Vious/LBAM_inpainting) |
2019|ICCV 2019|Free-Form Image Inpainting with Gated Convolution [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yu_Free-Form_Image_Inpainting_With_Gated_Convolution_ICCV_2019_paper.pdf) [[project]](http://jiahuiyu.com/deepfill2/)|
2019|ICCV 2019| FiNet: Compatible and Diverse Fashion Image Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Han_FiNet_Compatible_and_Diverse_Fashion_Image_Inpainting_ICCV_2019_paper.pdf) | Fashion
2019|ICCV 2019|SC-FEGAN: Face Editing Generative Adversarial Network with User's Sketch and Color [[pdf]](https://arxiv.org/pdf/1902.06838.pdf) [[code]](https://github.com/JoYoungjoo/SC-FEGAN)  | Face
2019|ICCV 2019| Human Motion Prediction via Spatio-Temporal Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Hernandez_Human_Motion_Prediction_via_Spatio-Temporal_Inpainting_ICCV_2019_paper.pdf) [[code]](https://github.com/magnux/MotionGAN) | Motion
2019|ICCV 2019| Copy-and-Paste Networks for Deep Video Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Copy-and-Paste_Networks_for_Deep_Video_Inpainting_ICCV_2019_paper.pdf) [[code]](https://github.com/shleecs/Copy-and-Paste-Networks-for-Deep-Video-Inpainting)| Video
2019|ICCV 2019| Onion-Peel Networks for Deep Video Completion [[pdf]](https://arxiv.org/abs/1908.08718) [[code]](https://github.com/seoungwugoh/opn-demo?tdsourcetag=s_pctim_aiomsg)| Video
2019|ICCV 2019 |Free-form Video Inpainting with 3D Gated Convolution and Temporal PatchGAN [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Chang_Free-Form_Video_Inpainting_With_3D_Gated_Convolution_and_Temporal_PatchGAN_ICCV_2019_paper.pdf) [[code]](https://github.com/amjltc295/Free-Form-Video-Inpainting) | Video
2019|ICCV 2019| An Internal Learning Approach to Video Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_An_Internal_Learning_Approach_to_Video_Inpainting_ICCV_2019_paper.pdf) | Video
2019|ICCV 2019| Vision-Infused Deep Audio Inpainting [[pdf]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Vision-Infused_Deep_Audio_Inpainting_ICCV_2019_paper.pdf) [[code]](https://github.com/Hangz-nju-cuhk/Vision-Infused-Audio-Inpainter-VIAI) | Audio
2019|AAAI 2020| Region Normalization for Image Inpainting [[pdf]](https://arxiv.org/abs/1911.10375) [[code]](https://github.com/geekyutao/RN) |
2019|AAAI 2020| Learning to Incorporate Structure Knowledge for Image Inpainting [[pdf]](https://arxiv.org/abs/2002.04170) [[code]](https://github.com/YoungGod/sturcture-inpainting) |
2020|CVPR 2020| Prior Guided GAN Based Semantic Inpainting [[pdf]](https://openaccess.thecvf.com/content_CVPR_2020/html/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.html)  |
2020|CVPR 2020| UCTGAN: Diverse Image Inpainting based on Unsupervised Cross-Space Translation [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.html) |
2020|CVPR 2020| Recurrent Feature Reasoning for Image Inpainting [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.html) [[code]](https://github.com/jingyuanli001/RFR-Inpainting) |
2020|CVPR 2020| Contextual Residual Aggregation for Ultra High-Resolution Image Inpainting [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/html/Yi_Contextual_Residual_Aggregation_for_Ultra_High-Resolution_Image_Inpainting_CVPR_2020_paper.html) [[code]](https://github.com/Ascend-Huawei/Ascend-Canada/tree/master/Models/Research_HiFIll_Model) |
2020|CVPR 2020| 3D Photography using Context-aware Layered Depth Inpainting [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Shih_3D_Photography_Using_Context-Aware_Layered_Depth_Inpainting_CVPR_2020_paper.pdf) [[code]](https://github.com/vt-vl-lab/3d-photo-inpainting) |
2020|CVPR 2020| Learning Oracle Attention for High-fidelity Face Completion [[pdf]](https://arxiv.org/pdf/2003.13903.pdf) |
2020|ECCV 2020| Rethinking Image Inpainting via a Mutual Encoder-Decoder with Feature Equalizations [[pdf]](https://arxiv.org/abs/2007.06929) [[code]](https://github.com/KumapowerLIU/Rethinking-Inpainting-MEDFE) |
2020|ECCV 2020| Short-Term and Long-Term Context Aggregation Network for Video Inpainting | Video
2020|ECCV 2020| Learning Object Placement by Inpainting for Compositional Data Augmentation |
2020|ECCV 2020| Learning Joint Spatial-Temporal Transformations for Video Inpainting [[pdf]](https://arxiv.org/abs/2007.10247) [[code]](https://github.com/researchmm/STTN) | Video
2020|ECCV 2020| High-Resolution Image Inpainting with Iterative Confidence Feedback and Guided Upsampling [[pdf]](https://www.researchgate.net/publication/341639944_High-Resolution_Image_Inpainting_with_Iterative_Confidence_Feedback_and_Guided_Upsampling) |
2020|ECCV 2020| DVI: Depth Guided Video Inpainting for Autonomous Driving [[pdf]](https://arxiv.org/abs/2007.08854) [[code]](https://github.com/ApolloScapeAuto/dataset-api) | Video
2020|ECCV 2020| VCNet: A Robust Approach to Blind Image Inpainting [[pdf]](https://arxiv.org/abs/2003.06816) |
2020|ECCV 2020| Guidance and Evaluation: Semantic-Aware Image Inpainting for Mixed Scenes [[pdf]](https://arxiv.org/abs/2007.08854) |
2021|WACV 2021| Hyperrealistic Image Inpainting with Hypergraphs [[pdf]](https://arxiv.org/abs/2103.10022) [[code]](https://github.com/GouravWadhwa/Hypergraphs-Image-Inpainting)|
2021|CVPR 2021| Generating Diverse Structure for Image Inpainting With Hierarchical VQ-VAE [[pdf]](https://openaccess.thecvf.com/content/WACV2021/papers/Wadhwa_Hyperrealistic_Image_Inpainting_With_Hypergraphs_WACV_2021_paper.pdf) [[code]](https://github.com/USTC-JialunPeng/Diverse-Structure-Inpainting)|
2021|CVPR 2021| Image Inpainting with External-internal Learning and Monochromic Bottleneck [[pdf]](https://arxiv.org/abs/2104.09068) [[code]](https://github.com/Tengfei-Wang/external-internal-inpainting)|
2021|CVPR 2021| PD-GAN: Probabilistic Diverse GAN for Image Inpainting [[pdf]](https://arxiv.org/abs/2105.02201) [[code]](https://github.com/KumapowerLIU/PD-GAN)|
2021|CVPR 2021| Image Inpainting Guided by Coherence Priors of Semantics and Textures [[pdf]](https://arxiv.org/abs/2012.08054) |
2021|CVPR 2021| FaceInpainter: High Fidelity Face Adaptation to Heterogeneous Domains [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_FaceInpainter_High_Fidelity_Face_Adaptation_to_Heterogeneous_Domains_CVPR_2021_paper.pdf) |
2021|CVPR 2021| TransFill: Reference-guided Image Inpainting by Merging Multiple Color and Spatial Transformations [[pdf]](https://arxiv.org/abs/2103.15982) [[code]](https://github.com/yzhouas/TransFill-Reference-Inpainting)|
2021|CVPR 2021| Prior Based Human Completion [[pdf]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhao_Prior_Based_Human_Completion_CVPR_2021_paper.pdf) | Human completion
2021|IJCAI 2021| Context-Aware Image Inpainting with Learned Semantic Priors [[pdf]](https://www.ijcai.org/proceedings/2021/0183.pdf) [[code]](https://github.com/WendongZh/SPL)|
2021|IJCAI 2021| Noise Doesn’t Lie: Towards Universal Detection of Deep Inpainting [[pdf]](https://www.ijcai.org/proceedings/2021/0109.pdf) | Inpainting detection
2021|TCSVT 2021| IID-Net: Image Inpainting Detection via Neural Architecture Search and Attention [[pdf]](https://ieeexplore.ieee.org/document/9410590) [[code]](https://github.com/HighwayWu/InpaintingForensics) | Inpainting detection
2021|WWW 2021| Progressive Semantic Reasoning for Image Inpainting [[pdf]](https://dl.acm.org/doi/10.1145/3442442.3451142) [[code]](https://github.com/sfwyly/PSR-Net)|
2021|ICCV 2021| Occlusion-Aware Video Object Inpainting [[pdf]](https://arxiv.org/abs/2108.06765) | Video
2021|ICCV 2021| Internal Video Inpainting by Implicit Long-range Propagation [[pdf]](https://arxiv.org/abs/2108.01912) [[code]](https://github.com/Tengfei-Wang/Implicit-Internal-Video-Inpainting)| Video
2021|ICCV 2021| Distillation-Guided Image Inpainting [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Suin_Distillation-Guided_Image_Inpainting_ICCV_2021_paper.pdf) | 
2021|ICCV 2021| Frequency-Aware Spatiotemporal Transformers for Video Inpainting Detection [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_Frequency-Aware_Spatiotemporal_Transformers_for_Video_Inpainting_Detection_ICCV_2021_paper.pdf) | Inpainting detection
2021|ICCV 2021| SLIDE: Single Image 3D Photography With Soft Layering and Depth-Aware Inpainting [[pdf]](https://export.arxiv.org/abs/2109.01068) [[project]](https://varunjampani.github.io/slide) | 
2021|ICCV 2021| FuseFormer: Fusing Fine-Grained Information in Transformers for Video Inpainting [[pdf]](https://arxiv.org/abs/2109.02974v1) [[code]](https://github.com/ruiliu-ai/fuseformer) | Video
2021|ICCV 2021| WaveFill: A Wavelet-Based Generation Network for Image Inpainting [[pdf]](https://arxiv.org/abs/2107.11027) | 
2021|ICCV 2021| CR-Fill: Generative Image Inpainting With Auxiliary Contextual Reconstruction [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zeng_CR-Fill_Generative_Image_Inpainting_With_Auxiliary_Contextual_Reconstruction_ICCV_2021_paper.pdf) [[code]](https://github.com/zengxianyu/crfill) | 
2021|ICCV 2021| Learning a Sketch Tensor Space for Image Inpainting of Man-Made Scenes [[pdf]](https://arxiv.org/abs/2103.15087) [[project]](https://ewrfcas.github.io/MST_inpainting/) | 
2021|ICCV 2021| Parallel Multi-Resolution Fusion Network for Image Inpainting [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Parallel_Multi-Resolution_Fusion_Network_for_Image_Inpainting_ICCV_2021_paper.pdf) | 
2021|ICCV 2021| Flow-Guided Video Inpainting With Scene Templates [[pdf]](https://arxiv.org/abs/2108.12845) | 
2021|ICCV 2021| High-Fidelity Pluralistic Image Completion With Transformers [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wan_High-Fidelity_Pluralistic_Image_Completion_With_Transformers_ICCV_2021_paper.pdf) [[project]](http://raywzy.com/ICT/)| 
2021|ICCV 2021| Learning High-Fidelity Face Texture Completion Without Complete Face Texture [[pdf]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_Learning_High-Fidelity_Face_Texture_Completion_Without_Complete_Face_Texture_ICCV_2021_paper.pdf) | Face
2021|WACV 2022| Resolution-robust Large Mask Inpainting with Fourier Convolutions [[pdf]](https://arxiv.org/pdf/2109.07161.pdf) [[code]](https://github.com/saic-mdal/lama) | 
2022|CVPR 2022| Dual-path Image Inpainting with Auxiliary GAN Inversion | 
2022|CVPR 2022| MAT: Mask-Aware Transformer for Large Hole Image Inpainting [[pdf]](https://arxiv.org/pdf/2203.15270.pdf) [[code]](https://github.com/fenglinglwb/MAT) | 
2022|CVPR 2022| Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding [[pdf]](https://arxiv.org/pdf/2203.00867.pdf) [[code]](https://github.com/DQiaole/ZITS_inpainting) | 
2022|CVPR 2022| Reduce Information Loss in Transformers for Pluralistic Image Inpainting | 
2022|CVPR 2022| MISF: Multi-level Interactive Siamese Filtering for High-Fidelity Image Inpainting [[pdf]](https://arxiv.org/pdf/2203.06304.pdf) [[code]](https://github.com/tsingqguo/misf) | 
2022|CVPR 2022| RePaint: Inpainting using Denoising Diffusion Probabilistic Models [[pdf]](https://arxiv.org/pdf/2201.09865.pdf) [[code]](https://github.com/andreas128/RePaint) |
2022|CVPR 2022| DLFormer:Discrete Latent Transformer for Video Inpainting | Video
2022|CVPR 2022| The DEVIL is in the Details: A Diagnostic Evaluation Benchmark for Video Inpainting [[pdf]](https://arxiv.org/pdf/2105.05332.pdf) [[code]](https://github.com/MichiganCOG/devil) | Video
2022|CVPR 2022| Towards An End-to-End Framework for Flow-Guided Video Inpainting [[pdf]](https://arxiv.org/pdf/2204.02663.pdf) [[code]](https://github.com/MCG-NKU/E2FGVI) | Video
2022|CVPR 2022| Inertia-Guided Flow Completion and Style Fusion for Video Inpainting | Video
2022|CVPR 2022| DLFormer:Discrete Latent Transformer for Video Inpainting | Video



------

To be updated...
