# Classification-of-Hyperspectral-Image
Classification of the Hyperspectral Image Indian Pines with Convolutional Neural Network

Hyperspectral images are images captured in hundrends of bands of the electromagnetic spectrum. This project is focussed at the development of Deep Neural Network for landcover classification in hyperspectral images. Land-cover classification is the task of assigning to every pixel, a class label that represents the type of land-cover.

Most of the existing studies and research efforts are following the conventional pattern recognition paradigm, which is based on the construction of complex handcrafted features. However, it is rarely known which features are important for the problem at hand. In contrast to these approaches, a deep learning based classification method that hierarchically constructs high-level features in an automated way, is proposed. In this project, exploitation of a Convolutional Neural Network, is taking part, to encode pixels’ spectral and spatial information and a Multi-Layer Perceptron to conduct the classification task.

This project is based on the paper "DEEP SUPERVISED LEARNING FOR HYPERSPECTRAL DATA CLASSIFICATION
THROUGH CONVOLUTIONAL NEURAL NETWORKS" by Makantasis et al. 

`Just to clarify, my code has nothing to do with the previously mentioned paper. I refer to it, because I follwed the same resoning to build my code.`

Description of the repository

1) Run the notebook "CreatetheDatasets", in order to create the Xtrain, Xtest, ytrain, ytest matrices. Matrices are saved in a numpy format.

2) Run the notebook "TrainTheModel", in order to train the model. The model is being saved including the weights.

3) Run the "Validation+ClassificationMaps", for validating the model and creating the clasification map.


| Patch Size | Overall Accuracy |
| ---------- | ---------------- |
|   5x5      | 83%              |
|7x7         | 88%              |
| 9x9        | 94%              |
|11x11       | 95%              |


![indian_pines](/images/indian_pines.jpeg)
