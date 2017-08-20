---
title: Data Set Description
author: Dr. Ziqian Dong, Gopi Prasad Marne
---
<img src=http://www.nyit.edu/files/communications_and_marketing/DIGITAL_LOGO_NYIT_RGB_HORIZ.png width="356" height="127" />

<br>

# Human Activity and User Recognition Using XSENS

 **Abstract:**  Human Activity and User Recognition database built from the recordings of 4  subjects performing activities of daily living (ADL) while carrying a 6 XSENS with embedded inertial sensors.

``` markdown
| Data Set Characteristics: | Time-series, Frequency Domain 
| Associated Tasks:         | Classification, Clustering
| Number of Features:       | 25
```
# DataSet: 
Download the data set for specific users with permission [**Download.**](https://drive.google.com/drive/folders/0B9ceq4Nu8R49S2o0Zzk4RWZPSjQ?usp=sharing)

## Data set Information:

The experiments have been carried out with a group of 4 volunteers within an age 19-31 years. Even person performed three activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS) wearing a xsens suit with 6 sensors placed on six positions(LOWER BACK, LEFT_WRIST, RIGHT_WRIST, LEFT_ANKLE, RIGHT_ANKLE, LEFT_FOOT). Using its embedded accelerometer and gyroscope, we captured 3-axis linear acceleration and 3-axial angular velocity at a constant rate of 100 Hz. Where 70% of the volunteers was selected for training and 30% for test the data.

The sensor signal (accelerometer and gyroscope) were pre-processed by applying noise filters used median filter with 3rd order. The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butter-worth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. The data was sampled in fixed-width sliding windows of 2 sec and 50% overlap (200 readings/window). From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Check the README.txt file for further details about this dataset. 

## Attribute Information:
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 25-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

### The data set includes the following files:
- 'Readme.txt'
- 'features_info.txt': Shows information about the variables used on the feature vector.
- 'features.txt': List of all features.
- 'Raw_Data_Set': Output from the xsens six sensors.
- 'Features_Data_Set': Obtained features after signal Processing for lowerback position.
- 'Mat-lab_Code.mat': Mat-lab files for filtering, separating body and gravity acceleration,   calculating magnitude, features exaction.

*Notes:*
- *Features are normalized and bounded within [0,1].*
- *Each feature vector is a row on the text file.*
- *The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).*
- *The gyroscope units are rad/seg.*
