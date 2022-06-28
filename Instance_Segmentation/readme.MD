# Instance Segmentation with AutoML for Images

**Segmentation consists to segregate objects in a visual environment**. **Instance Segmentation** is a form of image segmentation that detect instances of objects and demarcating their boundaries. It will detect the **polygon of the object or attribute** using a Computer Vision model. So it is possible to compute a surface of the object you want to detect. It can be useful for many use-cases (dust detection, corrosion detection, healthcare...).

<img src="https://github.com/retkowsky/Azure_AutoMLforImages_Learn/blob/main/Instance_Segmentation/animatedgif.gif">

Azure Automated ML for Images supports model training for computer vision tasks like image classification, object detection, and instance segmentation. Authoring AutoML models for computer vision tasks is currently supported via the Azure Machine Learning Python SDK. 
The resulting experimentation runs, models, and outputs are accessible from the Azure Machine Learning studio UI.

Content:
- Download some images files to train an instance segmentation model. In this example we will try to detect scratches from a metal piece.
- We will do the lalelling part usign Azure ML Data Labelling on the images
- Use AutoML for Images to build and train an instance segmentation model
- Do some advanced hyperparameter tuning using AutoML for Images advanced options
- Deploy the computer vision model into Azure Kubernetes Service
- You will test the model in a separate notebook

Let us start by training and deploying an instance segmentation detection model. 

The first Python notebook will download the training images, train and deploy an instance segmentation model to detect scratches from a piece of metal.
We will detect the region and the polygons of the scratches. Then we can compute a surface of these scratches as well:
https://github.com/retkowsky/Azure_AutoMLforImages_Learn/blob/main/Instance_Segmentation/1.%20Building%20an%20Instance%20Segmentation%20CV%20to%20detect%20scratches.ipynb

The second notebook will call the deployed model and do multiples tests on different images:
https://github.com/retkowsky/Azure_AutoMLforImages_Learn/blob/main/Instance_Segmentation/2.%20Calling%20the%20deployed%20CV%20model.ipynb

Then you can these two templates for your future projects.


