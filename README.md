# Pre-trained-Bert-with-attention-mechanism-to-classify-persion-poets-styles
In this research endeavor, the primary aim is for me to develop a text classifier endowed with attention mechanisms to discern the distinctive styles of renowned poets. My selection encompasses ten poets, and I meticulously partitioned the available data into two or three subsets: the training set, the test set, and, if deemed necessary, a validation set.

My approach entails the utilization of a pre-trained BERT model tailored for the Farsi language. Employing the classification token logit, which is found within BertPooler, I have engineered a classifier model to delineate the unique style of each poet. Subsequently, I have assessed the model's performance by gauging its loss, accuracy, and micro-average F1 score. Additionally, I have visualized the confusion matrix to gain insights into its predictive capabilities.

Furthermore, to optimize the model's performance, I conducted fine-tuning. Once again, I evaluated its effectiveness by measuring the loss, accuracy, and micro-average F1 score, and depicted the confusion matrix. Notably, this fine-tuning was executed using two distinct optimizers: Adam and SGD.

This comprehensive analysis and experimentation aim to shed light on the efficacy of attention-based models, pre-trained BERT architectures, and optimizer selection in the domain of Farsi poetry style classification.
