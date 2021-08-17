# Preprocess-Image-with-VGG16
# Table of Contents
Background
Problem Statement
Datasets
Framework
Results
Conclusion
References

# Background
Melanoma is the most severe kind of cancer that is becoming more common in the Western world. Melanoma is still thought to be caused primarily by exposure to the sun. Patients    with malignant (advanced-stage) melanoma have a wide range of prognoses, however public awareness initiatives encouraging early detection have resulted in considerable reductions in mortality rates. This disease primarily affects Caucasian men and women and has a terrible prognosis once it has spread to other parts of the body. As a result, early detection of this malignancy is critical for patient treatment success.
This research is carried out to classify melanoma images with Convolutional Neural Network(CNN) using the VGG16 pathway for preprocessing the images. 

# Problem Statement
The problem statement is to build a melanoma classifier given some sets of lesion images with high accuracy.

# Datasets
The Dataset is provided by SIIM ISIC and can be downloaded(Rotemberg et al., 2021). The dataset was made available for download as part of a live competition on the Kaggle platform from May 27, 2020 through August 20, 2020. It's licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) license and can be found at https://doi.org/10.34970/2020-ds01. This comprises of 2297 Image datasets belong to 9 classes of Images lesions:  which are 'actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma', 'vascular lesion'

![image](https://user-images.githubusercontent.com/74154451/129667183-2d6593e2-d7ed-4fd8-bca2-a4089cf4055c.png)

# Framework
![image](https://user-images.githubusercontent.com/74154451/129666087-42cd1b85-c5ad-44b4-8105-e4981d2aed22.png)

# Results
![image](https://user-images.githubusercontent.com/74154451/129665717-4441eb87-83ac-49d2-8849-58a61b6d611b.png)
![image](https://user-images.githubusercontent.com/74154451/129667525-8056bb34-0312-45ed-9583-2b6ebdea9e05.png)
![image](https://user-images.githubusercontent.com/74154451/129665775-c2085a53-7de9-4304-a0d1-6aac7e456146.png)
![image](https://user-images.githubusercontent.com/74154451/129665972-f3d74a33-dad2-4eae-820d-5d326a734088.png)
![image](https://user-images.githubusercontent.com/74154451/129666015-bca7dc65-4522-4d9c-bb4f-00cdc792e1c5.png)

# Conclusion

This Melanoma Classifier achieved a performance accuracy of 93%, precision of 1 and recall of 0.5% with Melanoma images, through preprocessing images with VGG16. This indicated that training images need to be adjusted before they can be trained on deep learning models especially when aiming at higher performance accuracy.

# References
📌Rotemberg, V., Kurtansky, N., Betz-Stablein, B., Caffery, L., Chousakos, E., Codella, N., Combalia, M., Dusza, S., Guitera, P., & Gutman, D. (2021). A patient-centric dataset of images and metadata for identifying melanomas using clinical context. Scientific Data, 8(1), 1–8.
📌Simonyan, K., & Zisserman, A. (2014). Very deep convolutional networks for large-scale image recognition. arXiv preprint arXiv:1409.1556.
📌https://www.kaggle.com/c/siim-isic-melanoma-classification/data
📌S. Albawi, T. A. Mohammed and S. Al-Zawi, "Understanding of a convolutional neural network," 2017 International Conference on Engineering and Technology (ICET), 2017, pp. 1–6, doi: 10.1109/ICEngTechnol.2017.8308186.
📌D. Stutz and L. Beyer, "Understanding Convolutional Neural Networks," 2014.
📌https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator

