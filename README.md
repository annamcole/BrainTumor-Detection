# BrainTumor-Detection


Dataset: https://www.kaggle.com/abhranta/brain-tumor-detection-mri

* Data: 1500 MRI images (labeled yes), 1500 MRI images (labeled no), 60 MRI images (unlabeled)

* This project only uses the labeled data (1500 yes, 1500 no)


preprocess: Preprocesses MRI images to crop down to the outter extremes of the skull.

model: Creates a CNN model to classify each image as either having a brain tumor or not.


Model Testing Accuracy: ~ 91%
