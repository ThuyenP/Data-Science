# Gender-Age-Classification

### Goal
This project goal is to build a classification model to determine age and gender of a person's facial image. The model was built using Keras and Tensorflow for training, and Numpy, Pandas, Seaborn, and Matplotlib for analyzing data. The dataset is based on the [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new) on Kaggle.

### Challenges and Future Implementation
#### Challenges:
The three main challenges I faced was:
1. Finding an even distributed dataset for gender and age
2. Increasing the accuracy for the model
3. Decreasing the validation loss for the model

I initially used the dataset [Faces: Age Detection from Images](https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset) on Kaggle, however, the collection is heavily skewed towards males and younger participants and led to inaccurate in model training. Thus, I decided to use the [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new) which has better distributed input. 

Regarding the accuracy and validation loss from the model, I attempted to increase the number epochs to test the threshold and decided to train the model between 25-30 epochs.

#### Future Implementation
In the future, I would continue to find a better way to improve this problem. Besides, I would try to make a website with this feature inside so that it could be used to classify a person's gender and age based on their input image

### Credits
Dataset: [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new) 
Tutorials: [Gender and Age Prediction using Keras Tensorflow | Deep Learning | Python](https://www.youtube.com/watch?v=vEJzsGXrB70)
