# Object Detection with Azure AutoML for Images

<img src = "animatedgif.gif">

Azure Automated ML for Images supports model training for computer vision tasks like image classification, object detection, and instance segmentation. 
Authoring AutoML models for computer vision tasks is currently supported via the Azure Machine Learning Python SDK. The resulting experimentation runs, models, and outputs are accessible from the Azure Machine Learning studio UI. 

Let us start by training and deploying an object detection model. You can find two Python notebooks here (mask vs nomask detection): 
- The first one will download the training images, use some existing labels for the objects we want to detect, train some custom vision models, and deploy the best model
into Azure. 
https://github.com/retkowsky/Azure_AutoMLforImages_Learn/blob/main/Object_Detection/1.%20AutoML%20for%20Images%20-%20Object%20Detection%20Part%201.ipynb

- The second notebook will call the deployed model and do multiples tests on different images. Then you can these two templates for your future projects.
https://github.com/retkowsky/Azure_AutoMLforImages_Learn/blob/main/Object_Detection/2.%20AutoML%20for%20Images%20-%20Object%20Detection%20Part%202.ipynb
