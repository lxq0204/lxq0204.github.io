---
title: "Improved Curriculum Learning using SSM for Facial Expression Recognition"
collection: publications
permalink: /publication/2024-05-24-paper-title-number-1
excerpt: 'This paper is about the Facial expression recognition'
date: 2020-10-01
venue: 'The Visual Computer'
slidesurl: # URL
paperurl: 'http://lxq0204.github.io/files/paper1.pdf'
citation: 'X. Liu and F. Zhou. &quot;Improved Curriculum Learning using SSM for Facial Expression Recognition.&quot; <i>The Visual Computer</i>. vol. 36, pp. 1635-1649, 2020.'
---

Facial expression recognition is an important research issue in the pattern recognition field. However, the generalization of the model still remains a challenging task. In this paper, we apply a strategy of curriculum learning to facial expression recognition during the stage of training. And a novel curriculum design method is proposed. The system first employs the unsupervised density–distance clustering method to determine the clustering center of each category. Then, the dataset is divided into three subsets of various complexity according to the distance from each sample to the clustering center in the feature space. Importantly, we develop a multistage training process where a main model is trained by continuously adding harder samples to training set to increase the complexity. To solve the problem that the model has a poor recognition accuracy for anger, fear and sadness, a self-selection mechanism is introduced in the test stage to make further judgment on the result of the main model. Experiment results indicate that the proposed model can achieve a satisfactory recognition accuracy of 72.11% on FER-2013 and 98.18% on CK+ dataset for 7-class facial expressions, which outperforms the other state-of-the-art methods.
