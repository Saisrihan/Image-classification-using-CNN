Retinal image classification is a critical task in medical image analysis, aiding in the diagnosis and treatment of various retinal diseases. 
This project aims to develop deep learning models capable of accurately classifying retinal images into different disease categories.

Three popular pre-trained models (VGG19, InceptionV3, MobileNetV2) are utilized as feature extractors. 
Custom dense layers are added on top of these models to adapt them to the specific classification task. The models are trained on a dataset of retinal images, consisting of training and validation sets.

After training, the models are evaluated on a separate test dataset to assess their performance in terms of accuracy and loss. 
Predictions are made on unseen test images, and the results are saved to a CSV file for further analysis.
