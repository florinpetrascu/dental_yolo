# DentalYOLO
This repository is dedicated to detecting dental issues using deep learning models, specifically YOLOv8 by Ultralytics.

## Dataset
The dataset contains X-rays from various patients with a total of:

Training set: 1,549 images
Testing set: 100 images
Validation set: 155 images

## Model Training
To train the YOLOv8 model to identify dental elements within X-rays, you can use the notebook provided: DentalYoloDetection.ipynb. This notebook is designed to streamline the process of setting up, training, and evaluating the model on dental radiographs.

## Dataset Configuration
Before starting training, make sure to update the paths for the dataset in the data.yaml file to match the location of your training, testing, and validation files.

## Classes
The model can detect the following 14 dental conditions and elements:

ID	  Label	Description

0	   IMP	Implant
1	   PRR	Prosthetic restoration
2	   OBT	Obturation
3	   END	Endodontic treatment
4	   CAR	Carious lesion
5	   BON	Bone resorption
6	   IMT	Impacted tooth
7	   API	Apical periodontitis
8	   ROT	Root fragment
9	   FUR	Furcation lesion
10	   APS	Apical surgery
11	   ROR	Root resorption
12	   ORD	Orthodontic device
13	   SRD	Surgical device

## Usage
We recommend using Google Colab for training the model, as it provides the necessary resources and computational power. Simply open the DentalYoloDetection.ipynb notebook, follow the instructions, modify the paths in data.yaml, and begin training.
