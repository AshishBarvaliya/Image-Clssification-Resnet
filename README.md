# Image-Clssification-Resnet
1) data_preparation.ipynb :
    - In this file all images of train, test and pred sets convert in to binary arrays.
    - for that you need to download the dataset : https://www.kaggle.com/puneet6060/intel-image-classification
2) modeling.ipynb:
    - Here i am using resnet for classification.
    - i trained model three time:
        - normal resnet :   got test accuracy: 75% .
        - resnet with 0.5 dropout : got test accu : 85% .
        - resnet with 0.7 dropout : got test accu : 78% 
    - Note: in the file only last model is available.           
