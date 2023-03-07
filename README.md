# Beauty-Classification

About Dataset

Content
The data set consists of a training set, a test set, a validation set and a consolidated set. Each of these sets contains two folders labeled as Beautiful and Average. For the training set there are 2000 images in the Beautiful folder and 2000 images in the Average folder. For the test set there are 150 images in the beautiful folder and 150 images in the Average folder. The validation set is similarly divided into 150 images of each type. The consolidated folder 2300 images in the Beautiful folder and 2300 images in the Average folder. The consolidated folder combines the images from the training, test and validation sets into a single set. This is convenient for users that want to create their own splits of training, test and validation images.
All images are 224 X 224 X 3 color jpg images. Images have been cropped to only show the face. All data sets were run through a duplicate image detector and all duplicate images were removed to prevent leakage between the data sets.

Acknowledgements
Images for the "Average" female images were selected from the CELEB data set.

Kaggle link : https://www.kaggle.com/datasets/gpiosenka/beauty-detection-data-set 
