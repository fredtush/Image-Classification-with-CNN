# Chest-X-ray-Image-Classification-with-CNN

![hello](https://github.com/fredtush/dsc-text-classification-lab/blob/master/images/pneumonia.png)

# Navigation

* [Project Overview](#Project-Overview)
* [Preprocessing](#Preprocessing)
* [Model Analysis](#Model-Analysis)
* [Future Work](#Future-Work)

# Important Links

* [Link to Data](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
* [Slideshow Presentation]()
* [Non-Technical Video Presentation]
* [Jupyter Notebook Full Modeling Process](https://github.com/fredtush/Image-Classification-with-CNN/blob/main/Image_Classification_with_Deep_Learning.ipynb)


# Project Overview

Tibabu hospital has observed an increase in Pneumonia infections. The hospital is understaffed, and cannot keep up with the high volume of patients. They approached Avengers LTD for a solution to help with the diagnosis. So to improve diagnosis of pneumonia using x-rays, tasked Avengers to come up with a solution.

Pneumonia is a serious lung condition that can be brought on by bacteria, viruses, or fungus. When someone has pneumonia, the alveoli (air sacs) are filled with fluid and pus, which makes breathing unpleasant, difficult, and restricts oxygen intake (reduced oxygen saturation). According to the WHO, pneumonia caused 14% of all deaths among children under the age of five in 2019. Both young people and the elderly are susceptible. A patient's clinical examination is used to diagnose pneumonia.

Machine learning in healthcare reduces the possibility of doing an improper examination. Therefore, Tibabu Hospital would like to put into practice a methodology that would enable them to detect pneumonia more precisely utilizing chest X-ray pictures. As a machine learning algorithm would sift through a vast amount of data to learn the most likely diagnosis, this would give patients more confidence in the diagnosis.


# Preprocessing

In order to preprocess the images, use of Keras' ImageDataGenerator to rescale the images' pixels (to a scale of 0 to 1), and resized the images to 156 x 156 px. Even though the x-rays seem to be in grayscale, their actual sizes have all 3 layers of a colored photograph (rbg). Thus, they remain untouched instead of converting them to grayscale. Below are two of the preprocessed images.


# Model Analysis

My final model was a Convolutional Neural Network with XXX accuracy. It has XXX blocks which include XXX convolutional layers, XXX max pooling layers, and XXX fully-connected layers.
    
## Metric Used

The algorithm will be considered a success if the predictions made by it have a:

1. Precision above 92%
2. Recall above 95%
3. Accuracy of 90% - 96%
4. The task is to build a model that can classify whether a given patient has pneumonia given their chest x-ray image.

Since this is an Image Classification problem, Deep Learning is the ideal solving method.


## Model Validation




## Model Conclusion and Recommendation



# Future Work

