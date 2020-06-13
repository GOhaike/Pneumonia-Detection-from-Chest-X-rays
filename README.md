# Pneumonia-Detection-from-Chest-X-rays

## Project Overview

Chest X-ray exams are one of the most frequent and cost-effective medical imaging examinations available. However, clinical diagnosis of a chest X-ray can be challenging and sometimes more difficult than diagnosis via chest CT imaging.

**In this project, I will analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, I will formally describe my model, the data that it was trained on, and a validation plan that meets FDA criteria.**

## Data Source

This NIH Chest X-ray Dataset is comprised of 112,120 X-ray images with disease labels from 30,805 unique patients with about 42 GB in size and might require GPU. To create these labels, the authors used Natural Language Processing to text-mine disease classifications from the associated radiological reports. The biggest limitation of this dataset is that image labels were NLP-extracted so there could be some erroneous labels but the NLP labeling accuracy is estimated to be >90%. The original radiology reports are not publicly available but you can find more details on the labeling process in this Open Access paper: "ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases." (Wang et al.).

**The labels include 14 common thoracic pathologies:**

 - Atelectasis
 - Consolidation
 - Infiltration
 - Pneumothorax
 - Edema
 - Emphysema
 - Fibrosis
 - Effusion
 - Pneumonia
 - Pleural thickening
 - Cardiomegaly
 - Nodule
 - Mass
 - Hernia

## Dataset Contents
- 112,120 frontal-view chest X-ray PNG images in 1024*1024 resolution (under images folder)

- Meta data for all images (Data_Entry_2017.csv): Image Index, Finding Labels, Follow-up #, Patient ID, Patient Age, Patient Gender, View Position, Original Image Size and Original Image Pixel Spacing.

## Project Steps

### 1. Exploratory Data Analysis(EDA)

The first part of THE project will involves exploratory data analysis (EDA) to understand and describe the content and nature of the data.

### 2. Building and Training Your Model

 **(a.)Training and validating Datasets**
 
From the finding from in EDA, appropriate training and validation sets for classifying pneumonia was chosen. 
 
 
TO BE continued .....


