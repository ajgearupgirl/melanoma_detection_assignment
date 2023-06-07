# MELANOMA DETECTION ASSIGNMENT

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.



 ## Table Of Contents:

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General-Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion



## Technologies-Used:

- Jupyter Notebook(Anaconda 3) - version 6.4.8
- Python3 - version 3.10
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- sklearn
- statsmodels
- Keras



## Conclusions:

Inference from the First Model:
1. The model is overfitting because we can see the difference in loss functions in training & validation.
2. The difference between Training Accuracy and Validation accuracy is around 20%, which seems to be a case of overfitting. But again, it's too early to decide.

Inference from Second Model:
1. There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
2. We can increase the epochs to increase the accuracy but it's too early for judgement.

Inference from Final Model:

1. The problem of Overfitting was solved by Data Augmentation
2. On doing Class Rebalance, we were able to improve the Overall Accuracy i.e., Training Accuracy and Validation Accuracy significantly.
3. On training the model with extra epochs, we were able to get a decent accuracy score of 88.2% on Training dataset and 82.8% on Validation dataset.



## Acknowledgements:

- This project was inspired by UpGrad CNN course
- References - google.com, stackoverflow.com



## Contact:

Created by ShreerakshaS - feel free to contact me!