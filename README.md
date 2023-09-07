# Comparative Study TensorFlow v/s Custom Neural Network Models



**Insurance Purchase Prediction - Weight & Bias Comparison**

**Overview:**
This repository conducts a comparative analysis of predictive modeling to determine whether an individual will purchase insurance using a self-generated dataset. The primary focus of this investigation centers on assessing the impact of diverse weight initialization methods and varying learning rates on the model's predictive performance.

**Dataset:**

**Description:**
The dataset employed in this study is a dataset created in-house, containing essential information about individuals, including attributes such as age, and affordibility and their insurance purchase decisions. The dataset is formatted as a CSV file.


**Models:**
Two distinct types of models were employed in this comparative analysis:

1. **Custom Neural Network Model:** A neural network model was constructed from scratch, providing full control over weight initialization techniques and learning rate parameters.

2. **TensorFlow Model:** TensorFlow, a widely-used deep learning framework, was harnessed to develop and train a neural network model for benchmarking against the custom model.

**Experiments:**

**Weight Initialization:**
This study delves into the influence of different weight initialization approaches, encompassing random initialization, Xavier/Glorot initialization, and He initialization. These techniques were applied to both the custom and TensorFlow models, enabling a comparative assessment of their effects on training and predictive performance.

**Learning Rate:**
To understand the convergence and performance implications, diverse learning rates can be evaluated, spanning a spectrum from small to large values (0.1, 0.01, 0.001).



**Usage:**

This repository provides the code necessary to replicate the experiments and conduct further analysis. 

**Conclusion:**

This comparative study offers invaluable insights into the significance of weight initialization and learning rate selection when training neural networks for binary classification tasks, exemplified through insurance purchase prediction. It provides guidance on optimizing model performance in practical applications.

**Contributing:**

Contributions to this repository are encouraged. Whether you have suggestions, enhancements, or additional experiments to propose, please feel free to open an issue or submit a pull request.
