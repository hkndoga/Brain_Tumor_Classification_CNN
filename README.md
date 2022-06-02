# erdos_artemis

Brain Tumor MRI Image Classification with Convolutional Neural Networks
=========================================================================

This convolutional neural network takes in MRI scans of the brain and spinal cord to detect the presence of tumors and classify their type. This was a project developed for the Erdos Institute Data Science Bootcamp, 2022, by the Artemis Group: Hakan Doga, Akarsh Mohan Konaje, Siying Li, and Erika Ordog.

Background
----------

Brain and spinal cord tumors are masses of abnormal cells in the brain or spinal cord that have grown out of control.
It is very important to distinguish between benign (non-cancerous) tumors and malignant tumors (cancers). 
MRI scans are considered the best way to look for tumors in these areas.

However, brain tumor diagnosis requires manual examination of MRI images by a radiologist. 
This process can be error-prone and time-consuming. 

The goal of this project is to improve the speed and accuracy of identifying and classifying brain tumors in MRI scans, which can facilitate the diagnostic process for healthcare provides and help patients receive faster and more accurate treatment.

<img src='./media/tumor_types.png' width=1000px>


Data
-------

The data was sourced from Kaggle (https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).
This dataset contains approximately 400 MRI scans, which we separated into twelve categories based on the tumor type (glioma, meningioma, pituitary, or none) and the plane of the anatomical coordinate system on which the MRI image was taken (coronal, sagittal, or transverse).


The anatomical coordinate system                                                   |  MRI examples
:---------------------------------------------------------------------------------:|:--------------------------------------------------------------------:
<img src="./media/mri_planes.jpg" alt="Anatomical Coordinate System" width=300px>  |  <img src="./media/mri_scans.png" alt="MRI Examples" width=400px>


The Baseline Model
----------------------
<img src='./media/cnn_baseline.png' width=600px>

The MobileNetV2 Model
--------------------------
<img src='./media/cnn.png' width=600px>

Results
---------------






