# Generative-Adversarial-Network
Generative Adversarial Networks(GAN) represent a cutting-edge approach to generative modeling within deep learning, leveraging architectures like convolutional neural networks. The goal of generative modeling is to autonomously identify patterns in input data, enabling the model to produce new examples that feasibly resemble the original dataset.

**Libraries used :**
* Torch
* Numpy
* Matplotlib
* tqdm

**Device = CUDA** : Code utilize GPU for training

Using TorchVision, upload **MNIST Dataset** which is used to provide hand-written digits.
Total image present in the dataset = 60,000

**Pre-Processing:**

* Batch_Size = 128
* Noise_Dimension = 64
* Learning_Rate = 0.0002
* Epochs = 10

Apply **Data Augmentation** pipeline to image:

Data Augmentation (Crop, Rotate, Zoom, Stretch, RGB Channel)

**Discriminator Network :**

Libraries : nn (Neural Network) , Summary

Discriminator uses Convolutional Neural Network (CNN) which include:

* in_channel = number of input channel in image
* out_channel = number of output channel produced by convolution
* Kernel_size = Size of Filter
* Stride = steps move across input image

  **Generator Network :**
  Random noise processed to generate fake images. Fake images must be similar to training dataset.

