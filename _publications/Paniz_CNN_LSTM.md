---
title: "A Hybrid CNN-LSTM Network with Attention Mechanism for Myoelectric Control in Upper Limb Exoskeletons"
collection: publications
category: conferences
permalink: /publication/Paniz_CNN_LSTM
excerpt: 'This paper introduces a novel attention-based sequence-to-sequence network for predicting upper-limb exoskeleton joint angles, enhancing the control of assistive technologies for individuals with upper limb impairments.'
date: 2024-06-24
venue: '2024 21st International Conference on Ubiquitous Robots (UR)'
paperurl: 'http://www.ece.ualberta.ca/~tbs/pmwiki/pdf/Sedighi-UR-2024.pdf'
bibtexurl: 'http://amrmarey15.github.io/files/Paniz_CNN_LSTM.bib'
citation: 'P. Sedighi, A. Marey, A. Golabchi, X. Li and M. Tavakoli, "A Hybrid CNN-LSTM Network with Attention Mechanism for Myoelectric Control in Upper Limb Exoskeletons," 2024 21st International Conference on Ubiquitous Robots (UR), New York, NY, USA, 2024'
---

<strong>Abstract</strong>

This paper introduces a novel attention-based sequence-to-sequence network for predicting upper-limb exoskeleton joint angles, enhancing the control of assistive technologies for individuals with upper limb impairments. By integrating EMG and IMU signals, our model facilitates real-time decoding of user intentions, generating precise movement trajectories for a 3-DoF cable-driven upper-limb exoskeleton. The implementation of an attention mechanism within an encoder-decoder architecture allows for the dynamic prioritization of the most pertinent EMG features and historical angular positions. Our model significantly outperforms existing EMG-based hand motion prediction methods in terms of prediction accuracy and responsiveness as demonstrated in evaluations. This approach not only offers a tailored response to varying sequence lengths and compensates for sensor unreliability but also introduces a level of generalization and adaptability previously unattainable in robotic rehabilitation and assistive devices. The implementation of the attention mechanism allows for adaptive learning, focusing on the most relevant signals for each user, thereby enhancing the system’s ability to learn and predict complex movement trajectories.
