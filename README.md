MNIST Neural Network with TensorFlow

This repository demonstrates how to install TensorFlow, visualize the MNIST handwritten digit dataset, and build a simple neural network classifier using TensorFlow/Keras.

📂 Project Structure

Tensorflow Installation.ipynb → Verifies TensorFlow installation.

Visualizing Mnist.ipynb → Loads and visualizes the MNIST dataset.

Mnist Neural Network.ipynb → Builds, trains, and evaluates a neural network model.

📊 Dataset: MNIST

70,000 grayscale images of handwritten digits (0–9).

Each image is 28×28 pixels.

Split into 60,000 training and 10,000 testing samples.

Automatically loaded from tf.keras.datasets.mnist.

🚀 Workflow

Install TensorFlow

import tensorflow as tf
print(tf.__version__)


Visualize Data

View shapes of training/testing data.

Plot first 10 handwritten digits with labels.

Build Neural Network

Input: 28x28 images flattened to 784 features.

Hidden layer: Dense (128 units, ReLU).

Output layer: Dense (10 units, Softmax).

Train Model

Optimizer: Adam

Loss: Categorical Crossentropy

Metrics: Accuracy

Trained for 5 epochs with batch size 32.

Evaluate Model

Test accuracy achieved: ~ 97–98% 🎉

📈 Example Visualization
plt.imshow(x_train[0], cmap="gray")
plt.title(f"Label: {y_train[0]}")
plt.show()

🛠️ Requirements

Python 3.8+

TensorFlow 2.x

Matplotlib

Install dependencies:

pip install tensorflow matplotlib

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.

✨ Crafted with TensorFlow for deep learning beginners.
