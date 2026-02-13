**Plant Disease Detection**

A Python project to detect plant diseases from leaf images using TensorFlow and PyTorch.

**Features**

Detect multiple plant diseases from leaf images.

**Implemented using TensorFlow and PyTorch.**

Supports training, validation, and prediction on new images.

Works with a custom dataset of 12 plant classes:
Brinjal, Cabbage BlackRots, Corn Gray leaf spot, Corn leaf blight, Corn rust leaf, Grape Rot, Ladies finger Bacterial Disease, Potato Early blight, Potato Lateblight, Potato healthy, Red Chilli Anthracnose, Soybean healthy.
Installation

Clone the repository:

git clone https://github.com/Pranjalchavanpatil/Plant-Disease-Detection.git
cd Plant-Disease-Detection


**Install dependencies:**

pip install tensorflow torch torchvision matplotlib numpy pillow


Upload your dataset into Our Dataset/Train and Our Dataset/Test folders.

TensorFlow Implementation

Uses Conv2D and MaxPooling2D layers with Dense layers for classification.

Train the model using model.fit() and validate on a subset.

Predict disease on new images using model.predict().

**PyTorch Implementation**

Custom CNNModel using nn.Conv2d, nn.MaxPool2d, and nn.Linear layers.

Train using DataLoader and CrossEntropyLoss.

Predict on new images using torch.softmax to get class probabilities.

**Dataset**

12 classes of plant leaves with diseases and healthy samples.

Organized in Train/ and Test/ folders for training and evaluation.

