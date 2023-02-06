# Food Vision
 
This project is based on Food101 dataset.

You can access the application [here](http://food-vision.eastus.cloudapp.azure.com/).

The dataset contains 1000 images per 101 classes. 

The split is 750 images for training and 250 images for testing per class.

I have used three pretrained models EfficientnetB0, EfficientnetB4 and EfficientnetB7.

All of the three models have been fine tuned by unfreezing all the layers.

<div align="center">

| Models | Loss | Accuracy |
| ------ | ---- | -------- |
| EfficientNetB7_fine_tune | 0.772 | 0.841 |
| EfficientNetB4_fine_tune | 0.863 | 0.825 |
| EfficientNetB0_fine_tune | 1.031 | 0.799 |
| EfficientNetB0_feature_extraction | 1.091 | 0.706 |
| EfficientNetB4_feature_extraction | 1.196 | 0.681 |
| EfficientNetB7_feature_extraction | 1.209 | 0.675 |

<i>Table comparing accuracy and loss of different models on the test dataset</i></div>

You can view the training results of the models on [Tensorboard](https://tensorboard.dev/experiment/3IOc29c8QNGGjRrmOjK9cg/).

You can access all the trained models [here](https://drive.google.com/drive/folders/1oVryuptgSuaB-K9sez8N5b1tj4qmp8-k?usp=share_link).
