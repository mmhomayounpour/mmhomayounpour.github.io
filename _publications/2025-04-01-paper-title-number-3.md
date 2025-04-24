---
title: "Self-Adaptive Revisiting Awareness for Enhancing Robustness and Generalization in Classification Task"
collection: publications
category: manuscripts
permalink: /publication/2015-02
excerpt: 'Deep neural network models are used today in various applications of artificial intelligence, the strengthening of which, in the face of adversarial attacks is of particular importance. An appropriate solution to adversarial attacks is adversarial training, which reaches a trade-off between robustness and generalization. This paper introduces a novel framework (Layer Sustainability Analysis (LSA)) for the analysis of layer vulnerability in an arbitrary neural network in the scenario of adversarial attacks. LSA can be a helpful toolkit to assess deep neural networks and to extend the adversarial training approaches towards improving the sustainability of model layers via layer monitoring and analysis. The LSA framework identifies a list of Most Vulnerable Layers (MVL list) of the given network. The relative error, as a comparison measure, is used to evaluate representation sustainability of each layer against adversarial inputs …'
date: 2024-04-24
venue: 'UnderReview'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231223002928'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

# Abstract
In the contemporary era, deep neural networks have become increasingly integral across various facets of our lives, making it crucial to address their vulnerabilities. This paper investigates the critical role of dynamically focusing on boundary samples, which reside in the uncertain regions of a model decision space, during the training process to enhance the robustness of neural networks. We introduce the Self-Adaptive Revisiting Awareness (SARA) strategy, which adapts to the evolving state of the model by navigating the decision boundary through the incorporation of a novel Confidence Guard loss. The related regularization term in this loss is designed to reinforce the robustness of the model by first identifying valuable alternative samples for each low-confidence or misclassified sample. These alternatives are discovered or generated through a gradient-based direction and are then used to augment the mini-batch during training iterations, dynamically increasing the mini-batch size. Incorporating these valuable samples into the Confidence Guard loss ensures that the model becomes more robust in handling manifold boundary samples throughout the training process. By concentrating on these critical samples, SARA effectively increases the support and continuity of data in the boundary regions of the model adaptively, thereby enhancing both adversarial robustness and generalization. This approach significantly improves model performance, achieving gains ranging from 2% to 16% on various public benchmark datasets in classification tasks. Overall, these results highlight the effectiveness of our method and suggest its potential for integration into strategies aimed at boosting robustness.

* Keywords: deep neural network, robustness, regularization, confidence guard

Suggested Citation: