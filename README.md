# Chest-X-Ray-Medical-Diagnosis-with-Deep-Learning
This project is an extension to the specialization course offered by Coursera "AI for Medical Specialization".


# Descreption
This work is an amalgamation of numerous smaller assignments from the Coursera 3 course. The purpose of this study is to employ a deep learning model to detect abnormalities in chest radiographs.

In order to identify abnormalities including cardiomegaly, mass, pneumothorax, and edoema, the project makes use of a DenseNet-121 model that has already been pretrained. This means that for all 14 pathologies with associated labels, this single model can provide accurate binary classification predictions.

Due to the low occurrence of the abnormalities within the X-ray sample, weight normalisation is conducted (class imbalance).

Finally, the GradCAM method is utilised to show exactly where the model is focusing its attention in order to produce the forecast. Marker finding, error analysis, training, and even deployment can all benefit from this technology.

# Dataset

Publicly available chest x-rays are being used in this study. There are 108,948 frontal X-ray images in this data set, representing 32,717 individual patients. Multiple text-mined labels indicating 14 different disease states are attached to each image in the dataset. In turn, these can be used to diagnose 8 distinct disorders by doctors. For this research, we've been focusing on a small (1000 photos) subset of the total collection.

Training will utilise 875 pictures.
There will be 109 photos used for checking.
420 test photos are available.
A CSV file with the actual labels for each X-ray is included with the dataset.

