# Facial-Recognition-Using-Transfer-Learning-with-VGG16-and-ResNet50
This project explores facial recognition using transfer learning with two state-of-the-art convolutional neural network architectures: VGG16 and ResNet50. Leveraging a publicly available facial recognition dataset, the pipeline includes data preprocessing, normalization, and data division into training, validation, and test subsets.

Both models are initialized with ImageNet pre-trained weights to benefit from learned visual features. The base layers are frozen to retain pre-trained knowledge, and custom classification layers are added for recognizing multiple facial categories. The models are trained and evaluated based on classification accuracy and loss.

Performance comparison between VGG16 and ResNet50 is carried out by analyzing their training and validation metrics. Visualizations of model accuracy and loss trends across epochs are provided to understand learning behavior. The best-performing models are saved and evaluated on a test subset to determine their real-world applicability.

This project demonstrates the effectiveness of transfer learning in facial recognition tasks and provides insights into choosing the right architecture for similar computer vision problems.
