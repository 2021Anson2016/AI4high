# ML-security
```
https://github.com/0FuzzingQ/ml-security
```

# APT Detection
```


```

# DGA(Domain Generating Algorithm)偵測
```
使用機器學習檢測DGA功能變數名稱（一）-SVM

https://github.com/phunterlau/dga_classifier
https://github.com/tokgolich/dga_classifier

https://www.r-bloggers.com/building-a-dga-classifier-part-1-data-preparation/
```
```
https://github.com/0FuzzingQ/dga_check
於機器學習識別DGA功能變數名稱
包括SVM , Word2Vec + LSTM兩種方法實現

acc:  SVM~90%    LSTM~99%

```
```
http://faculty.washington.edu/mdecock/papers/cchoudhary2018a.pdf
```
```
Predicting Domain Generation Algorithms with Long Short-Term Memory Networks
Jonathan Woodbridge, Hyrum S. Anderson, Anjum Ahuja, Daniel Grant
(Submitted on 2 Nov 2016)
https://arxiv.org/abs/1611.00791

Various families of malware use domain generation algorithms (DGAs) to generate a large number of pseudo-random domain names to connect to a command and control (C&C) server. In order to block DGA C&C traffic, security organizations must first discover the algorithm by reverse engineering malware samples, then generating a list of domains for a given seed. The domains are then either preregistered or published in a DNS blacklist. This process is not only tedious, but can be readily circumvented by malware authors using a large number of seeds in algorithms with multivariate recurrence properties (e.g., banjori) or by using a dynamic list of seeds (e.g., bedep). Another technique to stop malware from using DGAs is to intercept DNS queries on a network and predict whether domains are DGA generated. Such a technique will alert network administrators to the presence of malware on their networks. In addition, if the predictor can also accurately predict the family of DGAs, then network administrators can also be alerted to the type of malware that is on their networks. This paper presents a DGA classifier that leverages long short-term memory (LSTM) networks to predict DGAs and their respective families without the need for a priori feature extraction. Results are significantly better than state-of-the-art techniques, providing 0.9993 area under the receiver operating characteristic curve for binary classification and a micro-averaged F1 score of 0.9906. In other terms, the LSTM technique can provide a 90% detection rate with a 1:10000 false positive (FP) rate---a twenty times FP improvement over comparable methods. Experiments in this paper are run on open datasets and code snippets are provided to reproduce the results.
```
# Webshell Detection

```
https://github.com/0FuzzingQ/webshell

https://github.com/mylamour/blog/issues/6
```

# Malware Detection
```


```

# GAN and Security
```
Generative Adversarial Networks for Distributed Intrusion Detection in the Internet of Things
Authors: Aidin Ferdowsi, Walid Saad
https://arxiv.org/abs/1906.00567
```

# Adversarial Machine Learning attack
```
Adversarial Machine Learning at Scale
Alexey Kurakin, Ian Goodfellow, Samy Bengio
(Submitted on 4 Nov 2016 (v1), last revised 11 Feb 2017 (this version, v2))
https://arxiv.org/abs/1611.01236
```
