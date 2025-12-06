This project focuses on building a Flower Image Classification system using deep learning techniques under the domain of Applied AI. The goal is to automatically classify images of flowers into five categories: Daisy, Dandelion, Rose, Sunflower, and Tulip.

The dataset is loaded directly from TensorFlow Datasets (TFDS), eliminating the need for external downloads. Each image is uniformly resized and normalized to prepare it for training. A simple yet effective Convolutional Neural Network (CNN) architecture is used to learn visual features such as color, shape, and texture of different flowers.

The dataset is split into training and testing sets, enabling proper evaluation of model performance. During training, the model learns patterns using multiple epochs and provides feedback through accuracy and loss metrics. After training, the system generates predictions on unseen images and presents a textual description of each predicted flower class.

To evaluate performance, training and validation curves for both accuracy and loss are visualized, helping observe learning behavior and potential overfitting.

This project applies core concepts from Computer Vision, Deep Learning, and Transfer Learning, demonstrating how AI can be used to analyze natural images. The overall workflow includes loading data, preprocessing, model building, training, evaluation, and generating classification outputs.
