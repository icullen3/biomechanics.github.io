## Locomotion Mode Classification based on Wearable Sensosr data from Lower Limb Biomechanics 

### Introduction
Characterization of human movement and understanding of corresponding muscle coordination over various locmotion modes and terrain conditions is crucial for determining human movement strategies in environments more prevalent to community ambulation. Biomechanical data captured during locomotion, such as, Electromyography (EMG) signlas, can be used to anticipate transitions from one mode to another. Moreover, combination of multiple sensor data has the possibility to assist in data-driven model development for locomotion intent recognition using Machine Learning (ML) to greatly accelerate such tasks. 

### Problem Definition
The [dataset](http://www.epic.gatech.edu/opensource-biomechanics-camargo-et-al/) for the project has been acquired by EPIC Lab at Georgia Tech. The dataset contains 3-dimensional biomechanical and wearable sensor data (EMG - 11 sensors, Goniometer (GON) - 3 sensors, Inertial Measurement Unit (IMU) - 4 sensors) along with the kinematic and kinetic profiles of joint biomechanics (as a function of gait phase) from right side of the body of 22 able-bodied adults for 5 locomotion modes (e.g. level-ground or treadmill walking, stair-ascent, stair-descent, ramp-ascent and ramp-descent), different speeds (e.g. 28 speeds for treadmill walking) and heights (e.g. 4 height levels for stairs), multiple terain conidtions for each mode (walking speed, stair height, and ramp inclination) and multiple trials etc. [1].

<img src="https://user-images.githubusercontent.com/51376814/121802345-c82b8780-cc09-11eb-8c00-99bc77425916.png" alt="hi" class="inline"/>

In this project, we will develop subject-dependent classicifation models for 6 possible modes (standing and 5 locomotion modes) regardless of their terrain conditions based on biomechanics data captured from lower limb using EMG, GON, IMU etc. from able-bodied particiIMUpants for a single adult (e.g. AB21 from the dataset).

### Methods
In this project, we will use the aforementioned sesnor and biomechanical data as input features and corressponding locomotion modes as classification labels to develop supervised and unsupervised ML models such as k-Means Clustering, Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), Support Vector Machines (SVM), Random Forest (RF), Decision Trees (DT), and Neural Networks (NN).

### Broader Impact
The broader impact of this project would be future development of robotic assistive devices for targeted rehabilitation methods. and improvement of biomimetic controllers that better adapt to terrain conditions (practical scenarios).

### References
1. Camargo, J., Ramanathan, A., Flanagan, W., & Young, A. (2021). A comprehensive, open-source dataset of lower limb biomechanics in multiple conditions of stairs, ramps, and level-ground ambulation and transitions. Journal of Biomechanics, 119, 110320.
