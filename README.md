# Pneumonia-Detection-from-Chest-X-Rays


## Introduction

Pneumonia is an infection that can affect one/both of human lungs. It can be triggered by various infectious agents including bacteria, a virus, or even fungi. According to WHO, Pneumonia accounts for about 15% of all deaths of children below 5 years, killing approximately 800 thousand children annually. The risk of pneumonia is vast for many, especially in developing nations, most prevalent in South Asia and sub-Saharan Africa where millions of people face energy poverty and depend on polluting forms of energy. For these populations, accurate and fast diagnosis can save a lot of lives. It can guarantee timely access to treatment and save much needed time and money for those already experiencing poverty.
The diagnosis of pneumonia from chest X-rays is difficult for a lot of reasons:

1) Pneumonia appears very vaguely in a chest X-ray depending on the stage of the infection

2) Clinicians/ Doctors often have confusion in diagnosing  Pneumonia with other diagnoses such as multiple sclerosis  

3) Pneumonia has similrities with benign abnormalities

To address these issues, it is important to find a better method of diagnosis such as a deep learning algorithms. The algorithm needs to be very good in terms of accuracy as the algorithm is used for diagnosing a dangerous infection in humans.

In this project, the NIH Chest X-ray Dataset can be analyzed and trained using CNN to classify a given chest x-ray for the presence or absence of pneumonia. The predicted results can be tested by checking the accuracy with the available human radiologist-level data. We can say that it is a good approach for the development of a deep learning application for two reasons: 

•	Data availability is good enough for training deep learning models for image classification

•	Reduces clinical burnout by performing automated identification of most common scans and providing higher accuracy image reads.


## Dataset

This NIH Chest X-ray Dataset comprises of 112,120 front view X-ray images with disease labels from 30,805 unique patients. The disease labels were created using Natural Language Processing (NLP) to mine the associated radiological reports.

Meta data for all images;  Image Index, Finding Labels, Follow-up #, Patient ID, Patient Age, Patient Gender, View Position, Original Image Size and Original Image Pixel Spacing.

The labels include 14 common thoracic pathologies:

Atelectasis
Consolidation
Fibrosis
Infiltration
Pneumothorax
Edema
Emphysema
Effusion
Cardiomegaly
Nodule
Mass
Pneumonia
Pleural thickening
Hernia

The detailed description and the dataset can be found in the below link

URL: https://www.kaggle.com/nih-chest-xrays/data

