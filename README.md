# mri-image-segmentation

### Overview
The goal of this jupyter notebook is to classify each pixel of a cardiac MRI images, based on whether or not it corresponds to the left ventricle (=LV). The models are implemented with the TensorFlow machine learning Framework. For this repository the original images dataset has already been transformed to TFRecords in advance. Unfortunately, the dataset exceeds the github size limit. This project is part of the "Getting Started With Image Segmentation" Course of NVIDIA.

### Results
After training the CNN model with 100 epochs it provided an accuracy of 0.9976 and a dice coefficient of 0.9832.

### Orginal Dataset
- 256 x 256 grayscale dicom format
- Training set: 234 images
- Validation set: 26 images

**Dataset Source:** 

[1] Sunnybrook cardiac images from earlier competition https://smial.sri.utoronto.ca/LV_Challenge/Data.html

[2] This "Sunnybrook Cardiac MR Database" is made available under the CC0 1.0 Universal license described above, and with more detail here: https://www.cardiacatlas.org/studies/sunnybrook-cardiac-data/

[3] Attribution:
Radau P, Lu Y, Connelly K, Paul G, Dick AJ, Wright GA. "Evaluation Framework for Algorithms Segmenting Short Axis Cardiac MRI." The MIDAS Journal -Cardiac MR Left Ventricle Segmentation Challenge, http://hdl.handle.net/10380/3070
