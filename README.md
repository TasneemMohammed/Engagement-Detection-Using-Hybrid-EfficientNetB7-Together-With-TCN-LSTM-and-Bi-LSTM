# Engagement Detection for DAiSEE and VRESEE datasets Using Hybrid EfficientNetB7 Together With TCN LSTM and-Bi-LSTM

Students Engagement Level Detection in Online e-Learning Using Hybrid EfficientNetB7 Together With TCN, LSTM, and Bi-LSTM

Tasneem Selim, Islam Elkabani, Mohamed A. Abdou



[![General badge](https://img.shields.io/badge/Paper-Link-yellowgreen.svg)](https://ieeexplore.ieee.org/abstract/document/9893134)
[![General badge](https://img.shields.io/badge/Dataset-DAISEE-blueviolet.svg)](https://people.iith.ac.in/vineethnb/resources/daisee/index.html)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/students-engagement-level-detection-in-online/student-engagement-level-detection-four-class)](https://paperswithcode.com/sota/student-engagement-level-detection-four-class?p=students-engagement-level-detection-in-online)

[![Static Badge](https://img.shields.io/badge/Python-3.8-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow Badge](https://img.shields.io/badge/TensorFlow-2-orange.svg)](https://www.tensorflow.org/install)
[![Static Badge](https://img.shields.io/badge/matplotlib-3.9-babyblue.svg)](https://pypi.org/project/matplotlib/)
[![Static Badge](https://img.shields.io/badge/CV2-white.svg)](https://pypi.org/project/opencv-python/)
[![Static Badge](https://img.shields.io/badge/Tensorboard--colab-2.16-orange.svg)](https://pypi.org/project/tensorboard/)
[![Static Badge](https://img.shields.io/badge/numpy-blue.svg)](https://numpy.org/install/)
[![Static Badge](https://img.shields.io/badge/Keras--tcn-2.9.3-purple.svg)](https://pypi.org/project/keras-tcn/2.9.3/)
[![Static Badge](https://img.shields.io/badge/Keras-2.9-red.svg)](https://pypi.org/project/keras-tcn/2.9.3/)
[![Static Badge](https://img.shields.io/badge/Scikit--Video-brightgreen.svg)](https://www.scikit-video.org/stable/)
[![Static Badge](https://img.shields.io/badge/Video-Augmentation-white.svg)](https://github.com/okankop/vidaug)
[![Static Badge](https://img.shields.io/badge/sklearn-orange.svg)](https://pypi.org/project/scikit-learn/)



## Abstract:
Students engagement level detection in online e-learning has become a crucial problem due to the rapid advance of digitalization in education. In this paper, a novel Videos Recorded for Egyptian Students Engagement in E-learning (VRESEE) dataset is introduced for students engagement level detection in online e-learning. This dataset is based on an experiment conducted on a group of Egyptian college students by video recording them during online e-learning sessions. Each recorded video is labeled with a value from 0 to 3 representing the level of engagement of each student during the online session. Moreover, three new hybrid end-to-end deep learning models have been proposed for detecting student’s engagement level in an online e-learning video. These models are evaluated using the VRESEE dataset and also using a public Dataset for the Affective States in E-Environment (DAiSEE). The first proposed hybrid model uses EfficientNet B7 together with Temporal Convolution Network (TCN) and achieved an accuracy of 64.67% on DAiSEE and 81.14% on VRESEE. The second model uses a hybrid EfficientNet B7 along with Long Short Term Memory (LSTM) and reached an accuracy of 67.48% on DAiSEE and 93.99% on VRESEE. Finally, the third hybrid model uses EfficientNet B7 along with a Bidirectional LSTM and achieved an accuracy of 66.39% on DAiSEE and 94.47% on VRESEE. The results of the first, second and third proposed models outperform the results of currently existing models by 1.08%, 3.89%, and 2.8% respectively in students engagement level detection.


<div align="center">

 
#### FIGURE 1. The preprocessing of VRESEE video files

<img src="https://github.com/TasneemMohammed/Engagement-Detection-Using-Hybrid-EfficientNetB7-Together-With-TCN-LSTM-and-Bi-LSTM/blob/main/Figures/DatasetPreprocessing.gif" alt="Dataset Preprocessing" width="500" height="150">



#### FIGURE 2. The model architecture.
 <img src="https://github.com/TasneemMohammed/Engagement-Detection-Using-Hybrid-EfficientNetB7-Together-With-TCN-LSTM-and-Bi-LSTM/blob/main/Figures/modelArchitecture.gif" alt="The model architecture" width="500" height="300">




#### FIGURE 3. The EfficientNet B7 architecture.

<img src="https://github.com/TasneemMohammed/Engagement-Detection-Using-Hybrid-EfficientNetB7-Together-With-TCN-LSTM-and-Bi-LSTM/blob/main/Figures/EfficientNetB7Arch.gif" alt="The EfficientNet B7 architecture" width="650" height="350">
</div>

## Project Structure
There are several steps:

1- Prepare the datset
   * separate_data_into_4_classes.ipynb file is used to prepare the dataset
   * The dataset is divided into four categories, each category in a separate folder
   
2- Augmentation
   
3- Feature Extraction using EfficientNet B7
4- Train and tune the 

## Usage
• This project was prepared to run on Colab


## Cite

If any part of our paper or code is helpful to your work, please generously cite with:


```sh
@article{selim2022students,
  title={Students engagement level detection in online e-learning using hybrid efficientnetb7 together with tcn, lstm, and bi-lstm},
  author={Selim, Tasneem and Elkabani, Islam and Abdou, Mohamed A},
  journal={IEEE Access},
  volume={10},
  pages={99573--99583},
  year={2022},
  publisher={IEEE}
}
```
