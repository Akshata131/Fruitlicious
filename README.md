#  Kisanसफलशेती

Agriculture in India plays a predominant role in economy and employment.  Farming is of many kinds, orchard farming in India is getting popular day by day with time. There was a time when the only way to farming is by farmers but now a days as we have machines, technologies to do each and every smaller work of farming. By traditional process we can’t count the fruits as it is not only time-consuming, but it is also prone to error and tedious. It was also much more confusing to get the suggestion of fruit crops based on soil. Fortunately, technology continues to advance and develop answers to this kind of problem. One of these solutions is Fruit ripeness detection. If you need to know the condition of fruit, is it safe to eat or not because the acidity levels in unripe fruits are extremely high. The unripe give you a stomach ache, hurt your teeth, cause stomach gas, bloating, diarrhoea or other side effects.Counting is more than just count the fruits from trees. Counting is the efficient way to count the each and every type of the fruit in the orchard farming.  In the crop cultivation soil plays an important role. It is important for plants, animals rocks and living organisms. All of these helps in managing the fertility of the soil. Crop suggestion based on the soil type will give the actual suggestion that which crop is more suitable to that type of soil. 

# Technology for Kisanसफलशेती

# A. Fruit Un-Ripeness Detection

As we know eating the unripe fruit leads to many side-effects which will affect our health, so here we are trained the model which detect the ripeness and unripeness of the fruit we have used cvzone package to get the detection.		 
CVzone is a computer vision package that makes us easy to run like face detection, hand tracking, pose estimation, etc., and also image processing and other AI functions. At the core, it uses OpenCV and MediaPipe libraries. This is a Computer vision package that makes it easy to run Image processing and AI functions. Object Detection gives you the ability to detect objects present in live stream. This can predict the un- ripeness of a particular fruit.

# B. Fruit Count

We’ve used here the cvlib library. Detecting common objects in the scene is enabled through a single function call detect_common_objects(). It will return the bounding box co-ordinates, corrensponding labels and confidence scores for the detected objects in the image. This function takes an image formatted as NumPy array as an input and returns 3 things:
•	bbox: a list of bounding box coordinates for the detected objects.
•	label: list of labels for the detected object corresponding to the index of list of bounding box coordinates.
•	conf: list of confidence scores for the detection which shows how confident the model is that the predicted outcome is correct.
Here we want the count the fruits so we store label in the variable and with no of labels as it has gives the total count of fruit. Python code count the count of fruits present on a tree or anywhere. In this manner this can be useful in gardens and orchards and save their time in counting.

# C. Based on Soil Type Get The Crop suggestion

This project creates a model that can predict soil series with land type and according to prediction it can suggest suitable crops.In the model first it will segement the images,is the process of taking the data you hold and dividing it up and grouping similar data together based on the chosen parameters. Feature extraction refers to the process of generatimg the features that will subsequently be fed to a classifier in order to classify the image in one of the possible classes. And lastly based on all this processes classification can be done
![image](https://user-images.githubusercontent.com/86849097/198303439-beba9521-000c-4dd6-a601-3d96ce4518f5.png)

