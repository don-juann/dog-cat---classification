## Overview 
This project is created in order to address an image classification task to differentiate between images of dogs and cats. 

## Dataset
The dataset is named "dogsVScats" consists of 12500 images for each class, dogs and cats. However, the number of images was cut down to 5001 images for each class, totaling 10002 images.
Link to the dataset: www.kaggle.com/c/dogs-vs-cats/data

## Model Architecture
The Convolutional Neural Network (CNN) was used in this project, because of how CNNs can complex features from visual content, leading to high accuracy in tasks like image classification, object detection, and segmentation.
Sequential model was used with Keras layers such as Conv2D, MaxPooling2D, Flatten, Dense, Dropout during this project.

## Training
The dataset was split into training and validation sets with a ratio of 80:20. The model was trained using the Adam optimizer with a binary cross-entropy loss function, which outputs the probability value within the range of 0 to 1, where number closer to 0 is class of cats and number closer to 1 is class of dogs.

## Evaluation
The model's performance was evaluated using the training and validation sets. Metrics such as accuracy, precision, recall, and F1-score were calculated to assess the model's performance.
On top of that, there is a confusion matrix that shows the accuracy rate of model, which is around 98% on training dataset and 78% on validation dataset.

## Usage
Download the file "dogvcats.ipynb" to get to know the structure and training stage of the model.
Download the file "Готовый_классификатор_котов_и_собак.ipynb" to be able to use the model to predict the animal on the image.
- https://github.com/don-juann/dog-cat-classification
Download the model named "model_2.keras" from Google Drive, either upload it to your own Google Drive or upload it locally to the IDE you are currently using. 
- https://drive.google.com/file/d/1Q5ni0LubOLjZurbnsgSZj32Ysbg2veeW/view?usp=sharing
If you are working in Google Colaboratory, press 'CTRL+F9' on Windows or "Command+F9" on Mac to launch the model. 
Go to the last cell with empty function 'pred()' and write the address of your own image of dog or cat between brackets in a quotes, run the cell and get your answer.

## Creator
- Zhan Kazikhanov (Astana IT University)
- jkazikhanov@gmail.com
- https://github.com/don-juann
