# MultiModel Classification: Age Gender Race

One of my side projects for multioutput Convolutional Neural Networks based on Age, Gender and Race prediction model. The model is conducted on [PyTorch](https://pytorch.org/) to classify both age ang gender. I made a model project with pre-trained model [DenseNet](https://arxiv.org/abs/1608.06993). The model is trained on [FairFace benchmark](https://github.com/joojs/fairface). 

## Prerequisites

Thinks you have to install or installed on your working machine:

- Python
- Numpy 
- Pandas 
- Matplotlib 
- Jupyter Notebook
- Torchvision 
- PyTorch 

You can install the required packages by executing the following command.

`$ pip install -r requirements.txt`
### Environment
 - [Anaconda](https://www.anaconda.com/products/individual)

## Jupyter Notebook

[`Multioutput_CNN_Based_ Age_Gender_Classification.ipynb`](https://github.com/Shahrullo/MultiModelClassification_Age_Gender_Race/blob/main/MultiModel_Classification_Age_Gender_Race.ipynb)

The jupyter notebook describes the whole project. You can find the whole description inside the notebook.

### How to use it 
Open `Multioutput_CNN_Based_ Age_Gender_Classification.ipynb` on a jupyter notebook environment, or Google colab and run it.

## Training Result

#### Age Accuracy
```Got 2471 / 3709 with accuracy 66.62%```
![Confusion Matrix](https://github.com/Shahrullo/Multioutput_CNN_Age_Gender_Classification/blob/main/imgs/ageCF.png)

#### Images that our model mislabeled age with confident level
![](https://github.com/Shahrullo/Multioutput_CNN_Age_Gender_Classification/blob/main/imgs/mislabelAge.png)

#### Gender Accuracy
```Got 3473 / 3709 with accuracy 93.64%```
![Confusion Matrix](https://github.com/Shahrullo/Multioutput_CNN_Age_Gender_Classification/blob/main/imgs/genderCF.png)

#### Images that our model mislabeled gender with confident level
![](https://github.com/Shahrullo/Multioutput_CNN_Age_Gender_Classification/blob/main/imgs/mislabelGender.png)

## Author
- Shahrullohon Lutfillohonov. 
### For Contact
Twitter - [Shahrullo1](https://twitter.com/Shahrullo1)

Linkedin - [Shahrullohon Lutfillohonov](https://www.linkedin.com/in/shahrullohon-lutfillohonov-195b84203/)

## Licence
[MIT]()
