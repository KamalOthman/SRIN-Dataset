# SRIN-Dataset
SRIN stands for Social Robot Indoor Navigation Dataset. It consists of 2D colored images for room classification (termed SRIN-Room) and doorway detection (termed SRIN-Doorway). The main feature of SRIN dataset is that its images have been purposefully captured for short robots (around 0.5-meter tall) such as NAO humanoid robots. All images of the first version of SRIN were collected from several houses in Vancouver, BC, Canada.

## Main Folders
There are two main folders: 
1. SRIN-ROOM --> for room classification problem - 5 classes
2. SRIN-DOORWAY --> for doorway detection problem - 3 classes

## Contents of each folder
### Folders
1. original_raw_data: contains folders for each class that each class has all captured images without any changes.
2. all_data_for_training_evaluating: contains folders for each class after resizing and augmenting images.
3. Nao_images_for_testing: has all captured images by Nao humanoid robot.
4. our_trained_model: consists of 4 files: 
    1) weights.h5 
    2) model.json 
    3) accuracy.png
    4) loss.png
### Code Files
1. img_pred.py
2. Nao_prediction.py
3. train.py

## A Temporary Link for Downloading SRIN-DATASET
Click in the temporary link below to download SRIN-DATASET.tar.xz with size 1.2GB that contains the forementioned folders.

[Link to download SRIN-DATASET](https://www.dropbox.com/s/esjti0xr5iw0znk/SRIN-DATASET.tar.xz?dl=1)
