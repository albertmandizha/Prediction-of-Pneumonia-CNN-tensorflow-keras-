# Prediction of Pneumonia using Convolutional Neural Network on Chest X-ray Images

## Abstract:

This preliminary report explores the effectiveness of Convolutional Neural Networks (CNNs) for early detection of pneumonia in chest X-ray images. Utilizing a dataset from Kaggle, TensorFlow, and Keras frameworks, we trained a CNN model over two epochs. Data preprocessing techniques like resizing, normalization, and augmentation were applied to enhance model accuracy. Results indicate the CNN model achieved 94% accuracy, up from an initial 89%. However, model performance on normal data was lower due to dataset imbalance. Further investigation is needed to address this issue and improve model performance.

## Introduction:

Pneumonia is a significant cause of morbidity and mortality globally. Early detection is vital for effective treatment, with chest X-ray imaging being a common diagnostic tool. However, manual interpretation is time-consuming and subjective. CNNs offer automation potential, promising faster and more accurate diagnosis. This project aims to leverage CNNs for pneumonia prediction in chest X-ray images.

## Related Work:

### U-Net: Convolutional Networks for Biomedical Image Segmentation
The U-Net architecture proposed by Ronneberger, Fischer, and Brox offers an efficient solution for biomedical image segmentation, particularly with limited training data.

### ImageNet Classification with Deep Convolutional Neural Networks
Krizhevsky, Sutskever, and Hinton's work on ImageNet classification introduced the AlexNet architecture, setting new standards in deep learning.

## Dataset:

The Kaggle dataset comprises chest X-ray images labeled as normal and pneumonia. The imbalanced dataset contains 5,863 images, primarily from pediatric patients.

## Methods and Experiments:

We utilized TensorFlow and Keras to build the CNN model. Image resizing and CNN architecture design were crucial steps. The model was trained over two epochs, achieving significant performance improvements.

## Model Performance Evaluation Criteria:

Evaluation metrics such as accuracy, recall, precision, and F1-score are crucial for assessing model performance. Future work includes confusion matrix analysis and ROC curve evaluation.

## Conclusion and Future Works:

Preliminary results indicate improved model accuracy through resizing and two epochs of training. Further evaluation with a confusion matrix and ROC curve is planned to refine the model. Overall, this project lays the groundwork for future improvements in pneumonia detection using CNNs.

## Acknowledgment References:

[1] Krizhevsky, Alex, Ilya Sutskever, and Geoffrey Hinton. "ImageNet classification with deep convolutional neural networks." Proceedings of the 25th international conference on neural information processing systems, 2012.

[2] Ronneberger, Olaf, Philipp Fischer, and Thomas Brox. "U-net: Convolutional networks for biomedical image segmentation." arXiv preprint arXiv:1505.04597 (2015).

## GitHub Link for Project:
[GitHub Repository](https://github.com/albertmandizha/Prediction-of-Pneumonia-CNN-tensorflow-keras-)

