---
title: "Mean Teacher with Stochastic Restoration and Contrastive Learning for Domain Adaptive Object Detection"
collection: publications
category: manuscripts
# permalink: /publication/2010-10-01-paper-title-number-2
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2024-12-27
venue: 'SETN, AI Conference'
slidesurl: 'https://drive.google.com/file/d/1gLVk0At9F4ERdx0Os-nIiIWUMYic8HTo/view?usp=drive_link'
paperurl: 'https://dl.acm.org/doi/10.1145/3688671.3688755'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Test-time adaptation enables a pre-trained model to update its weights during inference, in order to adapt to a target domain that has a different distribution from the source domain. This adaptation occurs without any supervision and often in a more challenging source-free setting where no data from the source domain is used. While much attention has been given towards test-time adaptation for classification tasks, the significance of domain adaptation extends to various other applications and particularly object detection. Many studies consider a static target domain, which fails to simulate real-world conditions. In real-world applications, target domain is non-stationary and the target distribution can gradually change over time. In this work, we focus on continual test-time adaptation scenario, in which the target domain is continually changing over time. Leveraging the existing mean-teacher framework for object detection, we stochastically restore a small part of the student’s weights to the source pre-trained model weights during adaptation. Additionally, we aim to enhance performance by using contrastive learning. After a consistent experimental work it is shown that our proposed method compares favorably with the state of the art.
