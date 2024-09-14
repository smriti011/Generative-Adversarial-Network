# Generative-Adversarial-Network
Generative Adversarial Networks(GAN) represent a cutting-edge approach to generative modeling within deep learning, leveraging architectures like convolutional neural networks. The goal of generative modeling is to autonomously identify patterns in input data, enabling the model to produce new examples that feasibly resemble the original dataset.

**Libraries used :**
* Torch
* Numpy
* Matplotlib
* tqdm

Using TorchVision, upload **MNIST Dataset** which is used to provide hand-written digits.
Total image present in the dataset = 60,000

**Pre-Processing:**
Batch_Size = 128

Noise_Dimension = 64

Learning_Rate = 0.0002

Epochs = 10

Apply **Data Augmentation** pipeline to image:

Data Augmentation (Crop, Rotate, Zoom, Stretch, RGB Channel)
