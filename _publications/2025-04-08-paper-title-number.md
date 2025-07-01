---
title: "A Deep Reinforcement Learning-Based Robust Intrusion Detection System for Securing IoMT Healthcare Networks"
collection: publications
category: manuscripts
permalink: /publication/2025-06-08-paper-title-number-5
excerpt: >
  The Internet of Medical Things (IoMT) is transforming healthcare, but it introduces serious security risks. This paper presents HCLR-IDS, an advanced Intrusion Detection System leveraging CNN, ……
  <a href="/publication/2025-06-08-paper-title-number-5" style="color:gray; font-style:italic; text-decoration: none;">Click to read more……</a>

date: 2025-04-08
venue: 'Frontiers in Medicine'
paperurl: 'https://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2025.1524286/pdf'
citation: 'Shaikh, J. A., Wang, C., Sima, M. W. U., Arshad, M., Owais, M., Hassan, D. S., ... & Muthanna, M. S. A. (2025). A deep Reinforcement learning-based robust Intrusion Detection System for securing IoMT Healthcare Networks. Frontiers in Medicine, 12, 1524286.'
---

The Internet of Medical Things (IoMT) is transforming healthcare by enabling continuous remote patient monitoring, diagnostics, and personalized therapies. However, the widespread deployment of these devices introduces significant security vulnerabilities due to limited resources and inadequate network protocols. Intrusions within IoMT networks can compromise patient privacy, disrupt critical medical services, and jeopardize patient safety. To address these challenges, we propose HCLR-IDS, an advanced Intrusion Detection System (IDS) specifically designed for IoMT networks. The system integrates Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM) networks, and Reinforcement Learning (RL) techniques, namely Deep Q-Network (DQN) and Proximal Policy Optimization (PPO), to enhance the detection of evolving threats. The methodology begins with Enhanced Mutual Information Feature Selection (MIFS) to preprocess the CICIoMT2024 dataset, selecting the most relevant features while reducing noise and computational complexity. These selected features are then passed through a hybrid CNN-LSTM architecture. The CNN captures spatial patterns in network traffic, while the LSTM identifies temporal patterns. This dual feature extraction approach enables the system to effectively detect both static and dynamic characteristics of IoMT data. After feature extraction, the model incorporates DQN and PPO for decision-making. DQN optimizes actions based on Q-values, enhancing detection rewards, while PPO ensures stability in dynamic environments through a clipping mechanism. This combination of adaptive Q-learning and stable policy optimization significantly improves system robustness, ensuring effective real-time intrusion detection. The model demonstrates exceptional performance with binary classification accuracy of 0.9958, outperforming traditional IDS models. Additionally, it performs effectively in multi-class classification across 18 classes, achieving an accuracy of 0.7773. These results highlight that HCLR-IDS offers a reliable and efficient solution for securing IoMT healthcare systems.
