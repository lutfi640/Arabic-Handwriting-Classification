![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
# Arabic-Handwriting-Classification
### About the Project
Create a model to classify handwritten alphabet and number in Arabic. Created by using TensorFlow framework with CNN 2 dimension for image data. So when the model was created, it can predict new image to the belonging class.
### Dataset
The dataset was collected from Kaggle free open source dataset named [Arabic Handwritten Characters Dataset](https://www.kaggle.com/datasets/mloey1/ahcd1) and [Arabic Handwritten Digits Dataset](https://www.kaggle.com/datasets/mloey1/ahdd1) which is a CSV file. So we don't have to constrct the full image since it is already in the array format from the CSV.
### Preprocess
The preprocess part is not too much, just get the image to turn 90° to the right because it's on the different angle. And if you wish, you could potentially adding image augmentaton to the dataset.
### Modeling
I used Conolutional Neural Network algorithm to perform the classification with couples of layers ended with dense layer with softmax activation. Here is the full architecture of the model : 

![Model Architecture](https://github.com/lutfi640/Arabic-Handwriting-Classification/blob/main/Other/model.png)

and this is the result of the training which produced nice validatin accurcy about 0.96841.

![Training Curve](https://github.com/lutfi640/Arabic-Handwriting-Classification/blob/main/Other/Training%20curve.png)
