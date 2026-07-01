---
title: "Continual Test-Time Domain Adaptation for Object Detection via Contrastive Mean Teacher and Stochastic Restoration"
collection: publications
category: manuscripts
# permalink: /publication/2010-10-01-paper-title-number-2
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-11-24
venue: 'The European Journal on Artificial Intelligence'
paperurl: 'https://doi.org/10.1177/30504554251394323'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Test-time adaptation enables a pre-trained model to update its weights during inference, in order to adapt to a target domain that has a different distribution from the source domain. This adaptation occurs without any supervision and often in a more challenging source-free setting where no data from the source domain are used. While test-time adaptation has received considerable attention for classification tasks, domain adaptation is equally important for other computer vision tasks, such as object detection. Many approaches consider a static target domain, which fails to simulate real-world conditions, where the target domain is non-stationary and the target distribution can gradually change over time. In this work, we focus on the continual test-time adaptation scenario, in which the target domain is continually changing over time. Leveraging the mean teacher framework for object detection, we stochastically restore a small part of the student’s weights to the source pre-trained model weights during adaptation. Additionally, we aim to enhance performance by using contrastive learning. After a consistent experimental work, it is shown that our proposed method compares favorably with the standard mean teacher approach.
