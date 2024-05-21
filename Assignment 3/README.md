Assignment 3
Name: Maherun Nessa Isty
ID: 2021-2-60-086
CSE 366: Artificial Intelligence - Computer Vision Assignment
Objective:
This assignment is designed to give you practical experience in developing and training deep
learning models for computer vision tasks. You have the option to focus on either image
classification or object detection, using specific datasets and model architectures.
Option 1: Image Classification
• Dataset: Use the dataset available at this link. This dataset comprises various images that
you will classify into predefined categories.
Link: https://data.mendeley.com/datasets/brfgw46wzb/1
• Models to Implement: You are required to implement two of the following models:
• Custom CNN Model
• EfficientNet
• MobileNetV2
• DenseNet 121
• ResNet50
Train these models on the dataset and evaluate their performance using appropriate metrics. Provide a comparative analysis of the two models based on accuracy, training time, and complexity.
Introduction
The objective of this report is to implement and evaluate three state-of-the-art architectures:EfficientNet B0, DenseNet 121, and ResNet50 on the CoLeaf dataset.
The dataset contains 1006 leaf images categorized based on their nutritional deficiencies. The goal is to classify these images into one of the predefined categories: Boron, Iron, Potassium, Calcium, Magnesium, Manganese, Nitrogen, and Others. Then we dropped some image folders as they had a very low amount of data.
The number of images in each folder of Original Coleaf Dataset:
boron-B is:  101
calcium-Ca is:  162
iron-Fe is:  65
magnesium-Mg is:  79
manganese-Mn is:  83
nitrogen-N is:  64
phosphorus-P is:  149
potassium-K is:  96
Dataset Preparation and Augmentation
To enhance the dataset and improve the robustness of our models, data augmentation techniques are applied. These include random rotations, width and height shifts, shear transformations, zoom, and horizontal flips. The dataset is split into training, validation and test sets using a 70-20-10 split.
After augmenting the number of images of Augmented Data is 5590.
In each folder :
boron-B is:  670
calcium-Ca is:  768
iron-Fe is:  690
magnesium-Mg is:  691
manganese-Mn is:  622
nitrogen-N is:  687
phosphorus-P is:  720
potassium-K is:  742
Model training:
Here I have used three models to train the model.
1. EfficientNet B0
2.     DenseNet 121
3.     ResNet50
EfficientNet B0 emerged as a favorable option for its efficiency and performance, while DenseNet 121 and ResNet50 also demonstrated strong capabilities, each with its strengths in specific aspects of accuracy.
EfficientNet-B0 is designed for high performance with fewer resources through compound scaling and efficient blocks, making it ideal for resource-constrained environments.
DenseNet-121 promotes feature reuse and efficient gradient flow with dense connectivity, suitable for tasks requiring deep networks with fewer parameters.
ResNet-50 leverages residual connections to train very deep networks effectively, addressing vanishing gradient issues and excelling in complex image recognition tasks.
Results:
EfficientNet B0: Achieved a high accuracy (89.10%) and training time.
DenseNet 121: Provided robust accuracy (72.50%) with moderate training time.
ResNet50: Offered good performance (83.57%) with moderate training time.

 
 
 


