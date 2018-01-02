---
title: "ProtoNN: Compressed and Accurate kNN for Resource-Scarce Devices"
excerpt: "Machine learning for resource-constrained devices."
collection: "projects"
permalink: /projects/protonn
date: 2017-08-05
---

Machine learning for Several real-world applications require real-time prediction on resource-scarce devices such as an Internet of Things (IoT) sensor. Such applications demand prediction models with small storage and computational complexity that do not compromise significantly on accuracy. In this work, we propose ProtoNN, a novel algorithm that addresses the problem of real-time and accurate prediction on resource-scarce devices. ProtoNN is inspired by k-Nearest Neighbor (KNN) but has several orders lower storage and prediction complexity. ProtoNN models can be deployed even on devices with puny storage and computational power (e.g. an Arduino UNO with 2kB RAM) to get excellent prediction accuracy. ProtoNN derives its strength from three key ideas: a) learning a small number of prototypes to represent the entire training set, b) sparse low dimensional projection of data, c) joint discriminative learning of the projection and prototypes with explicit model size constraint. We conduct systematic empirical evaluation of ProtoNN on a variety of supervised learning tasks (binary, multi-class, multi-label classification) and show that it gives nearly state-of-the-art prediction accuracy on resource-scarce devices while consuming several orders lower storage, and using minimal working memory.'
{: .text-justify}

Links
---
[ICML publication](http://proceedings.mlr.press/v70/gupta17a.html)<br>
[EdgeML project wiki](https://github.com/Microsoft/EdgeML/wiki)