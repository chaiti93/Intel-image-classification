# Intel-image-classification
The [notebook ](https://github.com/chaiti93/Intel-image-classification-tensorflow-keras/blob/main/Intel_image_classification.ipynb) contains the code to develop a Deep Learning model (CNN) to classify 6 categories of images using the Transfer Learning approach with the help of Keras Pre-trained model (MobileNet V2). It consists of the following key blocks of the DL image classification pipeline -
1. Data preparation - Data loading, augmentation, and preprocessing
2. Model training and evaluation - Retrain a pre-trained model followed by Fine-tuning approach
3. Model prediction
4. Model optimization and compression - Convert Keras `.h5` model to `.tflite` for on-device deployment

 [**Mobile app implementation**](https://github.com/chaiti93/Flutter-intel-image-classify-app): Selected the best TFLite model and deployed it in a mobile application compatible with both Android and iOS using Flutter framework.

**Dataset used** : [Intel Image classification from Kaggle](https://www.kaggle.com/puneet6060/intel-image-classification)
