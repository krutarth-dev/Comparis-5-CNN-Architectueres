# Comparing-5-CNN-Architectueres

In this task, we implemented five different CNN architectures using the PyTorch library for the CIFAR-10 dataset. The goal was to create models with fewer than 10,000 parameters and achieve a minimum accuracy of the models on the CIFAR-10 test dataset.

We started by importing the required libraries and loading the CIFAR-10 dataset. The dataset was preprocessed by applying normalization and transforming the data into tensors.

Next, we defined five different CNN architectures:

### 1. Architecture 1: Simple CNN: This architecture consisted of a single convolutional layer, max pooling, and two fully connected layers.

### 2. Architecture 2: CNN with additional convolutional layers: This architecture had two convolutional layers, max pooling, and two fully connected layers.

### 3. Architecture 3: ResNet-18: We utilized the pre-trained ResNet-18 model, replaced the last fully connected layer, and fine-tuned it for CIFAR-10.

### 4. Architecture 4: VGG-16: We utilized the pre-trained VGG-16 model, replaced the last fully connected layer, and fine-tuned it for CIFAR-10.

### 5. Architecture 5: DenseNet-121: We utilized the pre-trained DenseNet-121 model, replaced the last fully connected layer, and fine-tuned it for CIFAR-10.

Each model was trained using the SGD optimizer and evaluated on the CIFAR-10 test dataset. The accuracy achieved by each model was recorded.

Finally, we created a comparison table that summarized the accuracy achieved by each architecture on the CIFAR-10 test dataset.

By implementing these different architectures, we were able to compare their performance on the CIFAR-10 dataset, considering the parameter limit and accuracy threshold. This task allowed us to explore the capabilities of various CNN architectures and assess their suitability for the CIFAR-10 classification task.
