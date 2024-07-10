# Celebrities Image Classifiers

### Goal
This project aims to classify certain celebrities based on the input dataset. 

### Resources
#### Dataset
The data being used to taken from the public source [Celebrity Face Image Dataset](https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset) on Kaggle. It includes 100 images for 18 people, including Angelina Jolie, Brad Pitt, Denzel Washington, High Jackman, Jennifer Lawrence, Johnny Depp, Kate Winslet, Leonardo Dicarprio, Megan Fox, Natialie Portman, Nicole Kidman, Robert Downey Jr., Sandra Bullock, Scarlett Johansson, Tom Cruise, tom Hanks, and Will Smith

#### Technologies
I used several libraries for data inspection, image and system control, and model training. In particular, I used:
* Data Inspections: Numpy, Pandas, Seaborn, and Matplotlib
* System and Image Control: Os, Shutil, and Cv2
* Wavelet Extraction on Images: Pywt
* Model Training: sklearn.svm, sklearn.preprocessing, sklearn.pipeline, sklearn.metrics
* Model Estimation: sklearn.ensemble, sklearn.linear_model, sklearn.pipeline, and sklearn.model_selection

### Challenges
#### Low-accuracy rate
With the dataset of 18 different people, the model could only give out approximately 60% prediction accuracy. This is due to the low number of images for each person. When tested with the dataset of only 5 people and each have 100 images, the accuracy for the model boosted to around 80% accuracy rate. Hence, in order to increase the model result, we could either decrease the number of interested people or increase the number of input images for each people. 

### Credits
Dataset: [Celebrity Face Image Dataset](https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset)
Inspired Tutorial: [Celebrities Classification | Model Training](https://www.youtube.com/watch?v=5Uc_m9CRWro)
