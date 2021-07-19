# 270300_Digit Recognizer

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/d7ad9871482a49b0b912db0b256cfade)](https://www.codacy.com/gh/NitinTyagi019/270300_Project2_submission/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=NitinTyagi019/270300_Project2_submission&amp;utm_campaign=Badge_Grade)

## Model Building

### The model used here is sequential.

* The method involves a relatively small number of parameters and hence training is relatively easy and fast.
* The system not only produces a classification of the digit but also a rich description of the instantiation parameters which can yield information such as the writing style.
* unlike many other recognition schemes, it does not rely on some form of pre-normalization of input images, but can handle arbitrary scalings, translations and a limited degree of image rotation.

### Parameters

* Conv2D creates a convolution kernel that is convolved with the layer input to produce a tensor of outputs.
* Activation function used here is ReLU activation function. it is used because ReLU is far more faster to compute. iT giveS you the power to build and train more deeper network
with it.
* Max-pooling helps in extracting low-level features like edges, points, etc.
* Adam Optimiser shapes your model into its most accurate form.
* The loss function is the guide to tell the optimiser whether it is moving right or wrong direction. Loss function used here is sparse_categorical_crossentropy.
* Metrics used here is Accuracy. Accuracy is proportional to true results among total no. of cases examined.

### Result

* Accuracy of this model comes out to be around 99.52 .


