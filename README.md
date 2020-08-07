# Traffic_Sign_Classification
 LeNet Deep Network to classifiy traffic signs. This is one of the models used in building self driving cars
 
 ## Table of contents
* [Technologies](#technologies)
* [Data](#data)
* [Model Details](#modeldetails)

## Technologies
The following technologies were used for this part of the project:

Python 3
Jupyter notebook
Pandas: Python package for data analysis
Matplotlib and Seaborn: Python 2D plotting library
Sklearn: Python package for modeling creation
Pickle: Python package for dataset segmentation 

## Data 
The dataset contains 43 different classes of images.

Classes are as listed below:

* ( 0, b'Speed limit (20km/h)') ( 1, b'Speed limit (30km/h)')
* ( 2, b'Speed limit (50km/h)') ( 3, b'Speed limit (60km/h)')
* ( 4, b'Speed limit (70km/h)') ( 5, b'Speed limit (80km/h)')
* ( 6, b'End of speed limit (80km/h)') ( 7, b'Speed limit (100km/h)')
* ( 8, b'Speed limit (120km/h)') ( 9, b'No passing')
* (10, b'No passing for vehicles over 3.5 metric tons')
* (11, b'Right-of-way at the next intersection') (12, b'Priority road')
* (13, b'Yield') (14, b'Stop') (15, b'No vehicles')
* (16, b'Vehicles over 3.5 metric tons prohibited') (17, b'No entry')
* (18, b'General caution') (19, b'Dangerous curve to the left')
* (20, b'Dangerous curve to the right') (21, b'Double curve')
* (22, b'Bumpy road') (23, b'Slippery road')
* (24, b'Road narrows on the right') (25, b'Road work')
* (26, b'Traffic signals') (27, b'Pedestrians') (28, b'Children crossing')
* (29, b'Bicycles crossing') (30, b'Beware of ice/snow')
* (31, b'Wild animals crossing')
* (32, b'End of all speed and passing limits') (33, b'Turn right ahead')
* (34, b'Turn left ahead') (35, b'Ahead only') (36, b'Go straight or right')
* (37, b'Go straight or left') (38, b'Keep right') (39, b'Keep left')
* (40, b'Roundabout mandatory') (41, b'End of no passing')
* (42, b'End of no passing by vehicles over 3.5 metric tons')

## Model Details
The network used is called Le-Net which is a convolutional neural network proposed by Yann LeChun. LeNet-5 CNN architecture is made up of 7 layers. The layer composition consists of 3 convolutional layers, 2 subsampling layers and 2 fully connected layers.
The following image shows the architecture of the network:

<img width="1129" alt="Screen Shot 2020-08-07 at 4 03 05 pm" src="https://user-images.githubusercontent.com/39994111/89614860-a4e8cb00-d8c8-11ea-9741-3e6f65b09640.png">

The following image shows the accuracy of the model:

<img width="384" alt="Screen Shot 2020-08-07 at 3 57 02 pm" src="https://user-images.githubusercontent.com/39994111/89614908-c5b12080-d8c8-11ea-8ed8-b14d6c436cf8.png">

The following image shows the prediction made with the model:

<img width="728" alt="Screen Shot 2020-08-07 at 3 56 43 pm" src="https://user-images.githubusercontent.com/39994111/89614971-e11c2b80-d8c8-11ea-9418-5344f3c64ebb.png">




