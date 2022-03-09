# Udacity-AI-for-Healthcare: Pneumonia Detection From Chest X-Ray imaging

## Problem description

The task is to analyze data from the NIH Chest X-ray Dataset (size 112120) and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. 
The project will build a CNN model which can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to 
the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, we need to formally describe the model, the data that it was trained on,
and a validation plan that meets FDA criteria.

The Dataset NIH Chest Xray Dataset - 112,000 chest x-rays with disease labels acquired from 30,850 patients. The disease labels were created using Natural
Language Processing (NLP) to mine the associated radiological reports. The labels include 14 common thoracic pathologies:

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

The biggest limitation of this dataset is that the accuracy of image labels is estimated >90% (since the labels were NLP-extracted with accuracy >90%) which may have some erros
in the labelings. The original radiology reports are not publicly available but you can find more details on the labeling process here.

Dataset Contents: 112,120 frontal-view chest X-ray PNG images in 1024*1024 resolution (under images folder) Meta data for all images (Data_Entry_2017.csv): 
Image Index, Finding Labels, Follow-up #, Patient ID, Patient Age, Patient Gender, View Position, Original Image Size and Original Image Pixel Spacing.

This project would require GPUs to train the deep learning model.
