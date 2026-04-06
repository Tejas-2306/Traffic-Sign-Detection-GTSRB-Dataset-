## Model

* Based on a standard CNN architecture (e.g., VGG/ResNet-like structure or sequential CNN)
* Modified according to the task requirements (layer tuning, number of filters, dense layers, etc.)
* Initialized with **ImageNet pre-trained weights (transfer learning)**
* Fine-tuned on the GTSRB dataset

### Key Modifications

* Adjusted output layer for GTSRB classes
* Tuned convolutional and dense layers
* Applied regularization techniques (if used: dropout/batch normalization)
