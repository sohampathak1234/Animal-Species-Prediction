# Animal-Species-Prediction
Code Clause Internship Project 2  

This project uses the YOLOv5 deep learning framework for object detection and classification to develop a system for identifying animal species in real-world images. The project involves collecting and labeling image datasets, training the YOLOv5 model, and integrating the model with a user interface for ease of use.

## Dataset
https://drive.google.com/drive/folders/1xBHb2l4Z70Z-oPXHR3QvZF3iaYZnSGx-?usp=sharing

## Preparing the Data

The data preparation process for this project involved collecting image datasets of different animal species and labeling the images with bounding boxes around the animals. This labeling process is necessary for training the YOLOv5 model to accurately detect and classify animal species.

Various classes are collected
- Tiger
- Giraffe
- Bear
- Lion
- Elephant
- Deer
- Wolf
- Bull
- Monkey
- Leopord
- Rhinoceros
- Hippo
- Cattle
The collected data was labelled

### Spliting the Data
The data is split into train and validation which is of the ratio 80:20
The prepared dataset is uploaded into the drive

### Cloning of Yolov5 and installing requirements
The yolov5 github repo was cloned into google colab
The data is mounted onto the google drive
The dataset is unzipped for further accessing
All the requirements for yolov5 are installed

### Data training and Validation
Mark the given config files as required
the training of model is done with image size 415, batch size - 31, epochs -100
Weights of yolov5s is given

## Inference
The inference files are uploaded (video, images)
The inference with the weights of best.pt is done

## Results
The final animal species detection system accurately identifies animal species in real-world images with a high degree of accuracy. The system can detect multiple animal species in the same image and outputs the predicted animal species with corresponding bounding boxes.

## Conclusion
This project demonstrates the potential of deep learning frameworks like YOLOv5 for object detection and classification in the field of animal species detection. The system developed in this project has practical applications in wildlife conservation, animal behavior studies, and more. The project can be extended to include more animal species and to improve the accuracy and efficiency of the detection system.

## Display
The detected image is displayed
### Predictions
> Image


![Photo](https://github.com/sohampathak1234/Animal-Species-Prediction/blob/main/Images/pred_cattle.jpg)


> Video


![Prediction Video](https://github.com/sohampathak1234/Animal-Species-Prediction/blob/main/Video/Elephant_pred.mp4)
