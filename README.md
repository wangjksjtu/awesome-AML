# Awesome Adversarial Machine Learning (AML) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
A curated list of awesome adversarial attack and defense papers, inspired by [awesome-adv-ml](https://github.com/yenchenlin/awesome-adversarial-machine-learning).

## Attack

### White-Box (Gradient-based)
* [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199). Szegedy et al., 2013. (L-BFGS)
* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572). Goodfellow et al., 2014. (FGSM)
* [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599). Moosavi-Dezfooli et al., 2015. (DeepFool)
* [The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528) Papernot et al., 2015. (JSMA)
* [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644). Carlini et al., 2016. (C&W)
* [Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533). Kurakin et al., 2016. (BIM)
* [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083). Madry et al., 2017. (PGD)
* [Boosting Adversarial Attacks with Momentum](https://arxiv.org/abs/1710.06081). Dong et al., 2017. (MIM)
* [EAD: Elastic-Net Attacks to Deep Neural Networks via Adversarial Examples](https://arxiv.org/abs/1709.04114). Chen et al., 2017. (EAD)
* [Generating Adversarial Examples with Adversarial Networks](https://arxiv.org/abs/1801.02610). Xiao et al., 2018. (AdvGAN)

### Black-Box (Gradient-free)
#### Transfer-based
* [Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697). Papernot et al., 2016.
* [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277). Papernot et al., 2016.
* [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770). Liu et al., 2016.

#### Score-based
* [ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models](https://arxiv.org/abs/1708.03999). Chen et al., 2017. (ZOO)
* [Practical Black-box Attacks on Deep NeuralNetworks using Efficient Query Mechanisms](http://openaccess.thecvf.com/content_ECCV_2018/html/Arjun_Nitin_Bhagoji_Practical_Black-box_Attacks_ECCV_2018_paper.html). Bhagoji et al., 2018. (PCA, random grouping)
* [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598). Ilyas et al., 2018. (NES)
* [Adversarial Risk and the Dangers of Evaluating Against Weak Attacks](https://arxiv.org/abs/1802.05666). Uesato et al., 2018. (SPSA)
* [AutoZOOM: Autoencoder-based Zeroth Order Optimization Method for Attacking Black-box Neural Networks](https://arxiv.org/abs/1805.11770). Tu et al., 2018.
* [Simple Black-box Adversarial Attacks](https://arxiv.org/abs/1905.07121). Guo et al., 2019.
* [Improving Black-box Adversarial Attacks with a Transfer-based Prior](https://arxiv.org/abs/1906.06919). Cheng et al., 2019.

#### Decision-based
* [Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/abs/1712.04248). Brendel et al., 2017. (Boundary Attack)
* [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598). Ilyas et al., 2018. (NES-LO)
* [Query-Efficient Hard-label Black-box Attack:An Optimization-based Approach](https://arxiv.org/abs/1807.04457). Cheng et al., 2018. (Optimization)
* [Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/abs/1904.04433). Dong et al., 2019. (Evolutionary Attack)
* [Guessing Smart: Biased Sampling for Efficient Black-Box Adversarial Attacks](https://arxiv.org/abs/1812.09803). Brunner et al., 2019. (Biased Boundary Attack)
* [HopSkipJumpAttack: A Query-Efficient Decision-Based Attack](https://arxiv.org/abs/1904.02144). Chen et al., 2019. (Boundary Attack++)

### Robust physical attack
* [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945) Eykholt et al., 2017. 
* [Synthesizing Robust Adversarial Examples](https://arxiv.org/abs/1707.07397) Athalye et al., 2017. (EOT, 3D adv-turtle)
* [ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector](https://arxiv.org/abs/1804.05810) Chen et al., 2018.
* [Physical Adversarial Examples for Object Detectors](https://arxiv.org/abs/1807.07769). Eykholt et al., 2018.
* [SemanticAdv: Generating Adversarial Examples via Attribute-conditional Image Editing](https://arxiv.org/abs/1906.07927). Qiu et al., 2019.
* [Adversarial Objects Against LiDAR-Based Autonomous Driving Systems](https://arxiv.org/abs/1907.05418) Cao et al., 2019.

### Attack across domains
* [Universal adversarial perturbations](https://arxiv.org/abs/1610.08401). Moosavi-Dezfooli et al., 2016
* [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204). Tramer et al., 2017.
* [Synthesizing Robust Adversarial Examples](https://arxiv.org/abs/1707.07397). Athalye et al., 2017. (EOT)
* [CAAD 2018: Iterative Ensemble Adversarial Attack](https://arxiv.org/abs/1811.03456). Liu et al., 2018. (ens-PGD, 5th in CAAD 2018)
* [Beyond Adversarial Training: Min-Max Optimization in Adversarial Attack and Defense](https://arxiv.org/abs/1906.03563). Wang et al., 2019. (better ens-attack, universal perturbataion and EOT)

## Defense
### Modifying the adversraial examples
* [A study of the effect of JPG compression on adversarial images](https://arxiv.org/abs/1608.00853). Dziugaite et al., 2016.
* [Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks](https://arxiv.org/abs/1704.01155). Xu et al., 2017.
* [Keeping the Bad Guys Out: Protecting and Vaccinating Deep Learning with JPEG Compression](https://arxiv.org/abs/1705.02900). Das et al., 2017.
* [Defending against Adversarial Images using Basis Functions Transformations](https://arxiv.org/abs/1803.10840). Shaham et al., 2018.

### Modifying the training schemes or models
* [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/abs/1511.04508) Papernot et al., 2015.
* [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083). Madry et al., 2017. (Adversarial Training, AT)
* [Extending Defensive Distillation](https://arxiv.org/abs/1705.05264). Papernot et al., 2017.
* [Mitigating Adversarial Effects Through Randomization](https://arxiv.org/abs/1711.01991). Xie et al., 2017.
* [Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://arxiv.org/abs/1802.00420). Athalye et al., 2018. (ICML 2018 best paper)
* [Curriculum Adversarial Training](https://arxiv.org/abs/1805.04807). Cai et al., 2018. (CAT)
* [Improved robustness to adversarial examples using Lipschitz regularization of the loss](https://arxiv.org/abs/1810.00953). Finlay et al., 2018.
* [Defensive Quantization: When Efficiency Meets Robustness](https://arxiv.org/abs/1904.08444). Lin et al., 2019.
* [Beyond Adversarial Training: Min-Max Optimization in Adversarial Attack and Defense](https://arxiv.org/abs/1906.03563). Wang et al., 2019. (Generalized Adversarial Training, GAT)

### Using other auxiliary tools
* [MagNet: a Two-Pronged Defense against Adversarial Examples](https://arxiv.org/abs/1705.09064). Meng et al., 2017. 
* [Defense against Adversarial Attacks Using High-Level Representation Guided Denoiser](https://arxiv.org/abs/1712.02976). Liao et al., 2017. (HGD)
* [Defense-GAN: Protecting Classifiers Against Adversarial Attacks Using Generative Models](https://arxiv.org/abs/1805.06605). Samangouei et al., 2018.
* [ComDefend: An Efficient Image Compression Model to Defend Adversarial Examples](https://arxiv.org/abs/1811.12673). Jia et al., 2018.
