# **MRI IMAGES CLASSIFICATION AS A DIAGNOSIS TOOLS FOR DETECTING TYPES OF BRAIN TUMOR DISEASE USING TRANSFER LEARNING VGG-16**

My college thesis code for bachelor degree.

This project aims to classify 4 types of condition while diagnosing human brain, which consist normal brain, pituitary tumor, meningioma tumor and glioma tumor. 12 kind of model variation were built with differences on augmented layer and learning rate on each model. Pre-processing data were using data reduction technique, which is undersampling technique to equalize data on each classes

Architecture model constructed sequently of:
- Input Layer
- Augmented Layer Variation
  - *Random Rotation*
  - *Random Zoom*
  - *Random Flip Horizontal*
  - *Random Flip Vertical*
  - *Mixed All Random*
- VGG-16 (Transfer Learning
- Output Layer (with Softmax Activation Function)

Hyperparameter configuration:

| Hyperparameter | Value / Type |
| ------------- | ------------- |
| Optimizer | *RMSProp*  |
| Learning Rate  | 0.01 / 0.001  |
| Loss Function | *Categorical Crossentropy*|

Prediction Test Example:

![gambar 1](https://github.com/40ssimo/4classtumorclassification/blob/main/pic/Picture1.png)
![gambar 2](https://github.com/40ssimo/4classtumorclassification/blob/main/pic/Picture2.png)
