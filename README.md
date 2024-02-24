# GAN-Images-detection-using-SVM-Classifier

## Objective:
This project aims to detect GAN-generated images using a two-class Support Vector Machine (SVM). 

The SVM classifier is trained on a dataset consisting of 150 live and fake images and then tested on a separate dataset containing 150 live and spoof images. Additionally, a Bagged Version of SVM is developed to compare its performance metrics (accuracy, F1-score, and recall) with the standalone SVM classifier.

## Conclusions:
The results indicate that the SVM classifier trained on the provided dataset achieved certain levels of accuracy, F1-score, and recall in detecting GAN-generated images. 

However, the bagged version of SVM showed significant improvements in classification performance, outperforming the standalone SVM model. 

These findings highlight the effectiveness of ensemble techniques, such as bagging, in enhancing the detection capabilities of SVM for identifying GAN-generated images.
