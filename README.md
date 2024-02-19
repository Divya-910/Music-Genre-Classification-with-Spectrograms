# Music-Genre-Classification-with-Spectrograms
Music Genre Classification with Spectrograms 

Project Overview
This project endeavors to classify music genres leveraging classic neural networks. The dataset comprises meticulously categorized songs, which are pre-processed into mel-spectrograms. These spectrograms serve as representative images of the music. Our investigation primarily revolves around exploring distinct neural network architectures, including CNNs, RNNs, and CRNNs.

Dataset Description
The dataset encompasses over 6000 instances of categorized songs. Each song undergoes pre-processing to generate mel-spectrograms, which form the foundational input data for our classification models.

Methodological Approach
Convolutional Neural Networks (CNNs):
Initially, we treat each spectrogram as an image and implement diverse CNN architectures to discern music genres.

Recurrent Neural Networks (RNNs):
Given the temporal dimension inherent in our data, we introduce RNNs to capture both short and long-term temporal features embedded in the songs.

Convolutional Recurrent Neural Networks (CRNNs):
Subsequently, we amalgamate CNNs and RNNs into a CRNN architecture, aiming to harness the local feature extraction capabilities of CNNs and the temporal summarization prowess of RNNs.

Model Training and Evaluation
The models undergo rigorous training using the provided dataset and are subsequently subjected to validation testing. We meticulously analyze the accuracy and loss curves to discern the efficacy of each model architecture.

Classifier and Regularization Techniques
Across all models, a softmax classifier is employed for multi-class classification. Furthermore, L2 regularization is utilized to mitigate overfitting tendencies and enhance generalization performance.

Dependencies
Python 3
TensorFlow
Keras
NumPy
Matplotlib





