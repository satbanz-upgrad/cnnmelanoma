# Project Name
> build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. 
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 9 Type of diseases are classified in the dataset. With dominance of "pigmented benign keratosis and melanoma" samples.
- The model overfits without using augmentation or Augmentor library with synthetic data.
- Using augmentation using zoom, flip and rotation same model was able to predict well. however with 20 epochs the model became more general. Might need tweaks in layers or number of epochs to increase accuracy.
- With synthetic data used the model accuracy got improved however more experiments are needed to increase explainability of the model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow - version 2.17.1
- Pandas - version 2.2.2
- Numpy - version 1.26.4
- Matplotlib - version 3.8.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
