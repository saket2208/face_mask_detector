# face_mask_detector
real-time face mask detector
Real-Time Face Mask Detection
Purpose :
Development of real-time face mask detector that can be used at various crowded places like shops, stations for the safety purpose of people.
This model uses inceptionV3 model as backbone which is in general not fit for real time purpose as it has a deep architecture but we are using it only till ‘mixed7’ layer which is not that deep as well as provide fucnctionality of Inception models which is to provide benefits of all 1*1, 3*3 and 5*5 filters.
MobileNet was a better architecture but used Inception for real-time as an experiment and it did work well after removing some layers from the end.
 



Language and Frameworks used :- Python, TensorFlow, OpenCV, keras
Data Source : Google images and github
Folder Strructure and Descriptions :
1.	Dataset folder : Contains data for training and validation
 

2.	Face_detector folder: contains res10_300x300_ssd_iter_140000.caffemodel architecture and well as trained weight.
a.	Deploy.prototxt : architecture of model
b.	res10_300x300_ssd_iter_140000.caffemodel : weights of model
3.	classifier.h5 file : contains trained classifier for mask or no mask along with weights and architecture to save time.
4.	Classifier.ipynb :  code to build, train and validate classifier model.
5.	Image_mask_detector.ipynb : code for mask detection in image.
Test data used comes directly from google images.
 
 
 
 
6.	Live_mask_detector.ipynb :  python notebook for real-time face mask dectection.
7.	Output.avi : saved video of life detections and predictions.
 
References :
1.	 opencv documentaions
2.	Tensorflow documentaions


