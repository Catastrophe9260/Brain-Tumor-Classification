# Brain Tumor Classification
Implemented a convolutional neural network (CNN) in Python using TensorFlow to differentiate between certain types of brain tumors. The model classifies 2D brain MRI scans as having a specific type of tumor or no tumor.

## Types of Brain Tumors
1. Glioma - growth of a tumor from glial cells which normally support neurons.
2. Meningioma - growth of a tumor from the meninges which are membranes around the brain.
3. Pituitary - growth of a tumor in the pituitary gland which are usually benign.

## The Dataset
The dataset is taken from Kaggle and consists of 512 x 512 brain MRI scans with 3 channels. I've also uploaded it to this repo as its a rather small one (~151 MB, also it has CC0 license)! But, just in case, here's the Kaggle link to where the dataset was uploaded: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset.

Below is how I structured my project folder - especially what the dataset directory looks like. Its broken down primarily into a training and testing set with a specific folder holding each type of brain tumor MRI scan and a folder with normal brain MRI scans.

![image](https://user-images.githubusercontent.com/33336845/235602598-d3f21c0c-e360-4809-8353-0c305ab1a688.png)

## Sample Images
Below are a few sample MRI scans and what they look like when plotted out in my notebook.

![image](https://user-images.githubusercontent.com/33336845/235606199-9891dbc2-8fef-46ed-ad95-feac79e7ea10.png)
![image](https://user-images.githubusercontent.com/33336845/235606235-f6063298-1ffc-4b73-b7c6-5f02fed8a461.png)

I used a Python 3.9 Miniconda environment with the required libraries installed using conda (primarily just tensorflow-gpu and its dependancies and a few other common data visualization libraries like Matplotlib). With that - feel free to take a look at my code, download it, and run it on your own!
