# Traffic-Sign-Recognition
A part of the Driver Assistance System

### Problem Definition:
To predict the different signs on road, which will assist the driver. The German Traffic Sign Benchmark is a multi-class, single-image classification challenge. Dataset can be downloded from Kaggle. 
- Single-image, multi-class classification problem
- 43 classes
- More than 50,000 images in total
- Large, lifelike database
- Dataset link: [GTSRB](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

### Libraries/Frameworks used:
- Tensorflow,
- Keras
- Scikit-learn
- Numpy
- Pandas
- Matplotlib

### Implementation:
1. Created two arrays for data and Labels
2. Built a sequential model
3. Architecture: 2 sets of Conv layers follwed by fully connected dense layers
4. Model is trained for 20 epochs
5. vaidation accuracy: 98.46% & training accuracy: 95.24%
6. Plotted the graphs of accuracy and loss
7. Predicted on test dataset
8. Deployed on web

### Prediction Results:
![t1](https://user-images.githubusercontent.com/59173499/133098452-26f2bb00-af5b-48cc-907e-2209ab8e461c.PNG)
![t2](https://user-images.githubusercontent.com/59173499/133098482-3e1b3f3a-9ef6-4105-ae68-8b5e0bd50947.PNG)
![t3](https://user-images.githubusercontent.com/59173499/133098507-dd112fd2-3bfe-46e1-8f5c-b2d418a147de.PNG)

### Conclusion:
The model successfully predicts most of the test images correclty. Further accuracy can be increased by implementing transfer learning or training for more epochs with large dataset. 
