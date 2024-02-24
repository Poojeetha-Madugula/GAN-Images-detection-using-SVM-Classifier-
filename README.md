# GAN-Images-detection-using-SVM-Classifier

## Objective:
The objective of this project is to detect GAN-generated images using a two-class Support Vector Machine (SVM).

The SVM classifier is trained on a dataset containing 150 live and fake images and tested on a separate dataset consisting of 150 live and spoof images. Additionally, a Bagged Version of SVM is developed for comparison purposes to assess its impact on accuracy, F1-score, and recall.

## Conclusions:
The project successfully implemented two-class SVM and a Bagged Version of SVM for detecting GAN-generated images. From the results:

The two-class SVM achieved an accuracy of 0.6267, F1-score of 0.5821, and recall of 0.52.
The bagged SVM demonstrated slightly improved performance with an accuracy of 0.6333, F1-score of 0.56, and recall of 0.4667.
While the bagged SVM showed a marginal increase in accuracy, it exhibited a slight decrease in F1-score and recall compared to the two-class SVM. Further optimization and fine-tuning may enhance the performance of both models.
