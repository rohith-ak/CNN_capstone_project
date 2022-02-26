# CNN_capstone_project

## DOMAIN: 
Automotive. Surveillance.


## CONTEXT:
Computer vision can be used to automate supervision and generate action appropriate action trigger if the event is predicted from the image of interest. For example a car moving on the road can be easily identified by a camera as make of the car, type, colour, number plates etc.

## DATA DESCRIPTION:
The Cars dataset contains 16,185 images of 196 classes of cars. The data is split into 8,144 training images and 8,041 testing images, where each class has been split roughly in a 50-50 split. Classes are typically at the level of Make, Model, Year, e.g. 2012 Tesla Model S or 2012 BMW M3 coupe.

	Train Images: Consists of real images of cars as per the make and year of the car.
	Test Images: Consists of real images of cars as per the make and year of the car.
	Train Annotation: Consists of bounding box region for training images.
	Test Annotation: Consists of bounding box region for testing images.

## Dataset: 
https://drive.google.com/drive/folders/1y6JWx2CpsOuka00uePe72jNgr7F9sK45?usp=sharing
Original dataset link for your reference only: https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder

## Reference: 
3D Object Representations for Fine-Grained Categorisation, Jonathan Krause, Michael Stark, Jia Deng, Li Fei-Fei 4th IEEE Workshop on 3D Representation and Recognition, at ICCV 2013 (3dRR-13). Sydney, Australia. Dec. 8, 2013.

### Process:
#### Step 1: Import the data
#### Step 2: Map training and testing images to its classes.
#### Step 3: Map training and testing images to its annotations.
#### Step 4: Display images with bounding box
#### Step 5: Design, train and test CNN models to classify the car.
#### Step 6: Design, train and test RCNN & its hybrids based object detection models to impose the bounding box or mask over the area of interest.
#### Step 7: Design a clickable UI which can automate tasks performed under milestone 1 
#### Step 8: Design a clickable UI which can automate tasks performed under milestone 2 
#### Step 9: Design a clickable UI based interface which can allow the user to browse & input the image, output the class and the bounding box or mask [ highlight area of interest ] of the input image 

### Output: Clickable UI based interface

![image description]()
