# anomaly-event-detection
Trafficvlm: A controllable visual language model for traffic video captioning(CVPR) 
简介：(Traffic video captioning)TrafficVLM。提出了一个名为TrafficVLM的多模态密集视频描述模型，能够生成交通视频事件的详细描述。
An attention-guided multistream feature fusion network for localization of risky objects in driving videos 
简介：ROL（Risky Object Localization）自动驾驶中对每个物体进行目标检测和跟踪后添加光流信息，从而给每一个object一个异常分数。
Graph (Graph): A Nested Graph-Based Framework for Early Accident Anticipation 
简介：TAA（Traffic Anomaly Anticipation）Graph-Graph 给定一个视频->提前预测事故，给每个帧一个异常分数。
A dynamic spatial-temporal attention network for early anticipation of traffic accidents 
简介：TAA（Traffic Anomaly Anticipation）DSTA 动态时空注意力网络（DSTA），结合动态时间注意力模块和动态空间注意力模块，能够从行车记录仪视频中选择关键时间片段和重要空间区域，帮助提前预测交通事故，并通过与门控循环单元（GRU）联合训练来提高预测精度。
Cognitive accident prediction in driving scenes: A multimodality benchmark 
简介：TAA（Traffic Anomaly Anticipation）CAP-DATA(包含一个新的数据集) 利用文本信息和驾驶员的注意力信息来辅助预测输出驾驶员注意力图以及caption信息。
Drama: Joint risk localization and captioning in driving 
简介：一个新的数据集，包含异常的定位以及caption标签。一种联合驾驶场景中的风险定位与自然语言风险解释的新研究方向，并收集了大规模数据集DRAMA，用于评估驾驶场景中多层次视觉描述的能力，同时对多任务预测架构进行了详细分析。
Abductive Ego-View Accident Video Understanding for Safe Driving Perception 
简介：TAA（Traffic Anomaly Anticipation）有一个新的数据集（bbox以及caption）、利用了CLIP可以异常定位输出caption等
Unsupervised traffic accident detection in first-person videos 
简介：TAD（Traffic Anomaly Detection）用于车载行车记录仪视频的无监督交通事故检测方法，其创新点在于通过预测交通参与者的未来位置并监控预测精度和一致性来检测异常，而无需依赖手动标注的数据集。
Lightning fast video anomaly detection via multi-scale adversarial distillation 
简介：VAD（Video Anomaly Detection）一种基于帧级别的快速视频异常检测模型，通过从多个高精度目标检测教师模型中蒸馏知识来检测异常，并引入对抗性蒸馏技术来提高学生模型的表现，从而在保持高速度的同时获得较好的检测效果。
Self-supervised likelihood estimation with energy guidance for anomaly segmentation in urban scenes(AAAI2024) 
简介：image anomaly segmantation 提出了一种基于能量引导的自监督框架，通过自生成异常像素来优化异常分割模型，并设计了两种估计器以捕捉异常概率，实现了在无需辅助数据的情况下对城市场景中的异常区域进行精确定位。
Unmasking anomalies in road-scene segmentation(ICCV ORAL2023) 
简介：image anomaly segmantation 提出了一种基于掩码分类的异常分割方法Mask2Anomaly，通过全局掩码注意力模块、掩码对比学习和掩码优化等技术创新，减少了对象边界的不确定性和假阳性率。
Diffusion for Out-of-Distribution Detection on Road Scenes and Beyond(ECCV2024) 
简介：image anomaly segmantation 通过引入ADE-OoD基准扩展了语义分割中的异常检测任务至自然图像领域，并提出了一种基于扩散分数匹配的OoD检测方法DOoD，能够应对高语义多样性场景下的异常检测。
OoDIS: Anomaly Instance Segmentation Benchmark(CVPR2024) 
简介：Anomaly Instance Segmentation 本文将现有的异常分割基准扩展到实例分割任务，以解决自动驾驶中对异常实例的识别问题，并评估了现有方法在该任务中的表现，指出该领域仍有待突破。
Placing Objects in Context via Inpainting for Out-of-distribution Segmentation(ECCV2024) 
简介：image anomaly segmantation 本文提出了通过扩散模型在图像中真实地添加物体的POC方法，能够扩展数据集以提升异常分割性能，并验证了在多个基准测试中的有效性，同时表明其对学习新类别也具有潜在优势。
Random Walk on Pixel Manifolds for Anomaly Segmentation of Complex Driving Scenes(ECCV2024) 
简介：image anomaly segmantation 提出了Random Walk on Pixel Manifolds (RWPM)方法，通过随机游走来优化像素嵌入，缓解复杂驾驶场景中像素嵌入空间的扭曲，进而提高异常分割中的异常评分精度。
Self-Supervised Predictive Convolutional Attentive Block for Anomaly Detection
简介：提出了一个自监督预测模块，通过掩蔽局部感受野并最小化重建误差来检测异常，该模块具有通用性，可以集成到多种最先进的异常检测方法中，从而提高图像和视频上的检测性能。
Memorizing Normality to Detect Anomaly: Memory-Augmented Deep Autoencoder for Unsupervised Anomaly Detection
简介：提出了一个增强记忆模块的自编码器MemAE，利用固定的正常数据记忆记录进行重建，增强对异常输入的重建误差，以提高自编码器在异常检测中的有效性。
Self-Supervised Masked Convolutional Transformer Block for Anomaly Detection 
简介：提出了自监督掩蔽卷积变换器模块（SSMCTB），结合3D掩蔽卷积层和变换器，能够灵活地进行信息掩蔽，并适用于多种神经网络架构，从而在多个基准上提升了异常检测的性能。
Generating Anomalies for Video Anomaly Detection with Prompt-based Feature Mapping
简介：提出了一种基于提示的特征映射框架（PFMF），用于解决虚拟和现实场景中异常检测的差距。PFMF使用异常提示生成现实场景中的未见异常，并通过域分类器和异常分类器缩小场景差异。实验表明，该框架在多个基准数据集上优于当前最先进的方法。
Feature Prediction Diffusion Model for Video Anomaly Detection
简介：提出了一种部分监督的视频异常检测方法，基于高斯混合变分自编码器（GMM-VAE）模型，利用正常样本学习特征表示。方法结合外观和运动异常，通过样本能量评分异常程度，实验结果在UCSD和Avenue数据集上优于现有方法。
Abnormal Event Detection and Localization via Adversarial Event Prediction
简介：基于高斯混合变分自编码器（GMM-VAE）的部分监督方法，提出了一种用于视频异常检测和定位的两流网络架构，结合RGB帧和动态流图像进行异常检测。实验验证了其在UCSD和Avenue数据集上的优越性能。
Self-Supervised Masked Convolutional Transformer Block for Anomaly Detection
简介：提出了一种自监督掩蔽卷积变换器模块（SSMCTB），结合3D掩蔽卷积层和变换器进行通道注意力控制，用于异常检测。此模块可以兼容多种神经网络架构，能够在多个基准上提升异常检测性能。
Video Anomaly Detection by Solving Decoupled Spatio-Temporal Jigsaw Puzzles
简介：通过解决一个直观且具有挑战性的预训练任务——时空拼图来进行视频异常检测。该方法将时空拼图任务分解为空间和时间维度，分别捕捉外观和运动特征，并通过全排列生成各种难度的拼图进行训练。实验表明，该方法在三个基准数据集上表现优异，尤其是在ShanghaiTech Campus数据集上，显著优于重建和预测方法。
Masked Video Distillation: Rethinking Masked Feature Modeling for Self-supervised Video Representation Learning
简介：提出了一个简单而有效的两阶段掩蔽特征建模框架（MVD）用于视频表征学习，称为掩蔽视频蒸馏。MVD首先预训练图像或视频模型，通过掩蔽特征建模从教师模型学习特征表示。设计了空间-时间协同教学方法，结合图像和视频教师模型的优势。实验证明，MVD框架在多个视频数据集上优于单一教师模型的性能，取得了最新的效果。
BatchNorm-based Weakly Supervised Video Anomaly Detection 
简介：针对弱监督视频异常检测提出了BN-WVAD方法，通过引入BatchNorm并利用特征偏差作为可靠的异常标准来检测异常片段。该方法设计了一种批级选择策略，能够在含有更多异常事件的视频中筛选出更多异常片段。实验结果在UCF-Crime和XD-Violence数据集上达到了最新的性能水平，AUC分别为87.24%和84.93%。
Self-Distilled Masked Auto-Encoders are Efficient Video Anomaly Detectors
简介：本文提出了一种基于轻量级掩蔽自编码器的异常事件检测模型，主要创新包括基于运动梯度加权令牌、集成教师和学生解码器以提高异常检测效果，并生成合成异常事件进行训练。实验表明，该模型在四个基准数据集上表现优异，并在1655 FPS的处理速度下达到了高效的检测性能，远超同类方法。
Learning Event-Relevant Factors for Video Anomaly Detection
简介：提出了一种基于因果生成模型的视频异常检测方法，旨在区分事件相关和无关因素，消除背景纹理和对象尺度变化等干扰。通过记忆增强模块学习事件相关因素的原型，并利用反事实学习策略指导异常预测。实验结果证明该方法在消除干扰因素和提高检测准确性方面效果显著。
中文异常检测综述 中文的文章 


