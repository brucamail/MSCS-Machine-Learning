Motivation
Overview
Image classification is a fundamental problem in computer vision with significant real-world applications. The ability to automatically identify and categorize objects within images has revolutionized various industries. For example, in retail, image classification is used for automatic classification of goods, improving inventory management. In healthcare, it aids in classifying potential skin diseases. Manufacturing benefits from it for inspecting products on assembly lines for defects.

This technology not only automates tasks but also opens doors to new possibilities in areas like autonomous vehicles, security surveillance, and content moderation, making it a critical area of research and development.

Purpose
While numerous models already achieve high accuracy on this dataset, my primary goal is to leverage this well-established benchmark as a learning opportunity and deepen my practical knowledge of CNN architectures.

Leveraging such a well establihsed dataset allows me to experiment with various hyperparameters, such as batch size, activation functions, learning rate, and dropout, to observe their impact on model performance and gain insights into the fine-tuning process of buidling a CNN.

The Data
Fashion-MNIST is a dataset of Zalando's article images it consists of a training set of 60,000 observations and a test set of 10,000 observations categorized in 10 classes. It was published to be a replacement to the original MNIST dataset used for benchmarking machine learning algorithms.

Each observation is a 28x28 grayscale image, associated with a numeric label from 0 to 9 according to the following mapping:

'T-shirt/top',
'Trouser',
'Pullover',
'Dress',
'Coat',
'Sandal',
'Shirt',
'Sneaker',
'Bag',
'Ankle boot'
The data will be directly sourced from Keras datasets.

Thorughout the notebook I'll leverage ideas from papers and other notebooks, providing the links to their work for further reference.