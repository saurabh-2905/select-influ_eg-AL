# select-influ_eg-AL

In this work, the focus is on selecting the most influential examples for active learning. It was observed that, during incremental learning if the training data is not unique compared to the previous training data, the performance of the model tends to drop. Thus it is important to select the most unique samples to train the model during active learning. It was also observed in this work, if the model is trained with the subset of whole dataset containing only unique samples, it performs better compared to when trained on the whole dataset.

To determine the uniqueness of the sampels, two different weighting methods were used which assigned weigths between 0 to 1 to each sample. Following were the 2 techniques used:
1. Weight using soft-voting probabilities
2. weights using L2-distance

In this work, various machine learning concepts like active learning, unsupervised learning, semi-supervised learning, incremental learning were used.  
