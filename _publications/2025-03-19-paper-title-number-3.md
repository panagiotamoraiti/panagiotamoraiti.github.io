---
title: "Technical Report for the 5th CLVision Challenge at CVPR: Addressing the Class-Incremental with Repetition using Unlabeled Data - 4th Place Solution"
collection: publications
category: manuscripts
# permalink: /publication/2010-10-01-paper-title-number-2
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-03-19
venue: 'arXiv'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://arxiv.org/abs/2503.15697'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

This paper outlines our approach to the 5th CLVision challenge at CVPR, which addresses the Class-Incremental with Repetition (CIR) scenario. In contrast to traditional class incremental learning, this novel setting introduces unique challenges and research opportunities, particularly through the integration of unlabeled data into the training process. In the CIR scenario, encountered classes may reappear in later learning experiences, and each experience may involve only a subset of the overall class distribution. Additionally, the unlabeled data provided during training may include instances of unseen classes, or irrelevant classes which should be ignored. Our approach focuses on retaining previously learned knowledge by utilizing knowledge distillation and pseudo-labeling techniques. The key characteristic of our method is the exploitation of unlabeled data during training, in order to maintain optimal performance on instances of previously encountered categories and reduce the detrimental effects of catastrophic forgetting. Our method achieves an average accuracy of 16.68% during the pre-selection phase and 21.19% during the final evaluation phase, outperforming the baseline accuracy of 9.39%.
