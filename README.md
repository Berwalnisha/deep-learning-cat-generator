# Deep Learning Image Generator - Cats
This Jupyter Notebook demonstrates the implementation of a deep learning model to generate images of cats using PyTorch.
### Table of Contents

* Introduction
* Usage
* Model Architecture
* Training and Evaluation
* Results
* Dependencies
* License

### Introduction
* The goal of this project is to create a deep learning model that can generate realistic-looking images of cats. This can be useful for various applications, such as art generation, image augmentation, or as a tool for pet lovers.
  
### Usage
* To use the deep learning model for generating cat images, follow these steps:

Open the deep-learning-cat-generator.ipynb Jupyter Notebook.
Run all the cells in the notebook to train the model and generate a new cat image.
The generated cat image will be saved as generated_cat.png.

### Model Architecture
The deep learning model used in this project is a Generative Adversarial Network (GAN). The architecture consists of a Generator and a Discriminator network, as detailed in the notebook.
Training and Evaluation
The model was trained using the PyTorch framework. The training process involves alternating between training the Discriminator and the Generator networks, with the goal of improving the quality of the generated images.
The training and validation loss convergence graphs are provided in the notebook, showing the model's performance during the training process.

### Results
The trained model was able to generate new cat images that closely resemble the real cat images from the dataset. The generated image is saved as generated_cat.png.
Dependencies
The project uses the following main dependencies:

* PyTorch
* NumPy
* Matplotlib
* Torchvision

The complete list of dependencies is specified in the notebook's environment.

