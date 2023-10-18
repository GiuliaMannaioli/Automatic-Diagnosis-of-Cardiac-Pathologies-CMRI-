# Automatic-Diagnosis-of-Cardiac-Pathologies-CMRI-
Implementation of Automatic Diagnosis of Cardiac Pathologies using cardiac magnetic resonance imaging (CMRI). 

Cardiac pathologies can lead to life-threatening complications, such as heart failure and sudden cardiac arrest. Early detection of 
these pathologies is essential for effective treatment and prevention of complications.

To address this challenge, we used a **dataset** of 150 subjects and extracted features to classify **MRI 
images** into one of five diagnostic classes, including healthy controls and four cardiac pathologies. 

The **dataset** was split into a training-validation set and then the algorithm is used with the given test set. 

I tried three algorithms to classify the subjects: **Random Forest, Linear SVM** and **Non-Linear SVM**. 

I also tried to do some preprocessing such as **PCA** and I tried to segment the images that presented some 
issues.


## References

The main articles consulted during the development of this project are in the folder docChallenge.


## Dataset

The dataset used for this project is sourced from the [ACDC Challenge](https://acdc.creatis.insa-lyon.fr/). It consists of a training-validation set with 100 subjects and a test set with 50 subjects. The dataset provides cardiac MRI images and their corresponding segmentation maps for end systole (ES) and end diastole (ED) phases. The segmentation map includes the following structures (with respective labels):

0. Background
1. Right ventricle cavity (RV)
2. Myocardium (MY)
3. Left ventricle cavity (LV)
