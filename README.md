# Awesome Adversarial Machine Learning (AML) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 
A curated list of awesome adversarial attack and defense papers, inspired by [awesome-adv-ml](https://github.com/yenchenlin/awesome-adversarial-machine-learning).

## Attack

### White-Box (Gradient-based)
* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572), Goodfellow et al., 2014. (FGSM)
* [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599), Moosavi-Dezfooli et al., 2015. (DeepFool)
* [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644), Carlini et al., 2016. (C&W)
* [Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533), Kurakin et al., 2016. (BIM)
* [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083), Madry et al., 2017. (PGD)
* [Boosting Adversarial Attacks with Momentum](https://arxiv.org/abs/1710.06081), Dong et al., 2017. (MIM)
* [EAD: Elastic-Net Attacks to Deep Neural Networks via Adversarial Examples](https://arxiv.org/abs/1709.04114), Chen et al., 2017. (EAD)


### Black-Box
#### Transfer-based
* [Practical Black-Box Attacks against Machine Learning](https://arxiv.org/abs/1602.02697), Papernot et al., 2016.
* [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277), Papernot et al., 2016.
* [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770), Liu et al., 2016.

#### Score-based
* [ZOO: Zeroth Order Optimization based Black-box Attacks to Deep Neural Networks without Training Substitute Models](https://arxiv.org/abs/1708.03999), Chen et al., 2017. (ZOO)
* [Practical Black-box Attacks on Deep NeuralNetworks using Efficient Query Mechanisms](http://openaccess.thecvf.com/content_ECCV_2018/html/Arjun_Nitin_Bhagoji_Practical_Black-box_Attacks_ECCV_2018_paper.html), Bhagoji et al., 2018. (PCA, random grouping)
* [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598), Ilyas et al., 2018. (NES)
* [Adversarial Risk and the Dangers of Evaluating Against Weak Attacks](https://arxiv.org/abs/1802.05666), Uesato et al., 2018. (SPSA)
* [Improving Black-box Adversarial Attacks with a Transfer-based Prior](https://arxiv.org/abs/1906.06919), Cheng et al., 2019.

#### Decision-based
* [Decision-Based Adversarial Attacks: Reliable Attacks Against Black-Box Machine Learning Models](https://arxiv.org/abs/1712.04248), Brendel et al., 2017. (Boundary Attack)
* [Black-box Adversarial Attacks with Limited Queries and Information](https://arxiv.org/abs/1804.08598), Ilyas et al., 2018. (NES-LO)
* [Query-Efficient Hard-label Black-box Attack:An Optimization-based Approach](https://arxiv.org/abs/1807.04457), Cheng et al., 2018. (Optimization)
* [Efficient Decision-based Black-box Adversarial Attacks on Face Recognition](https://arxiv.org/abs/1904.04433), Dong et al., 2019. (Evolutionary Attack)
* [Guessing Smart: Biased Sampling for Efficient Black-Box Adversarial Attacks](https://arxiv.org/abs/1812.09803), Brunner et al., 2019. (Biased Boundary Attack)
* [HopSkipJumpAttack: A Query-Efficient Decision-Based Attack](https://arxiv.org/abs/1904.02144), Chen et al., 2019. (Boundary Attack++)

## Defense
TBD
