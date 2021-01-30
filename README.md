# Aerial-Image-Recognition
The goal is to make submissions to Aerial Image Recognition challenge and to explore various machine learning techniques.

We will find here 3 different models. The first model is a Basic CNN that provides 50% accuracy. The second model is a FastAI pretrained model resnet18, it provides 95 accuracy made. The last mode is built with TensorFlow, it provides 81% accuracy.


The challenge can be found here: https://competitions.codalab.org/competitions/27749

Solved by:
- Phan Anh VU (phanav)
- Mohamed Salem MESSOUD (mdsalem17)


## Archive Structure
```
.
├── README.md                   - Here, you are :)
├── image_data                  - contains training, validation, and test images for fastai
├── tf_image_data               - contains the training images with the right directory structure, so that tensorflow can operate
├── public_data                 - contains all available data in plain text format
|
└── starting_kit                - contient les fichiers sources (.cpp) et entêtes (.h).
    ├── BasicCNN.ipynb          - contient the BasicCNN model with the answers to the asked questions with 50% accuracy (+/- 2%)
    ├── tensorflow_model.ipynb  - contains the tensorflow model with 81% accuracy (+/- 5%)
    ├── fastai_model.ipynb      - contains the best model built with FastAI with 95% accuracy (+/- 2%)
└──
```

## Instructions :
- Make sure you have TensorFlow and FastAI, you will find guidance for installing these packages when they are needed.
- You should upload the public_data from the challenge website, if you want to run the files
