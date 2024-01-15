# Style-transfer


## Project Overview
This project implements a neural style transfer algorithm as described in the seminal paper "Image Style Transfer Using Convolutional Neural Networks" by Gatys et al. It uses PyTorch and a pre-trained VGG19 network to transfer the artistic style from one image (the style image) onto the content of another image (the content image), effectively merging these aspects to create a new, stylistically altered image.

## Features
- VGG19 for Feature Extraction: Utilizes the VGG19 model, a deep convolutional neural network pre-trained on the ImageNet dataset, for extracting style and content features from images.
- Style Transfer: Combines the content of one image with the style of another using the technique of Gatys et al.
- Gram Matrix Representation: Employs Gram matrices to capture and apply artistic styles from the style image to the content image.
- Flexible Image Inputs: Supports image inputs from various sources, including URLs and local files.
- Customizable Parameters: Allows tweaking of style weights, content weights, and other parameters to explore different styles.

## Installation
To get started with this project, you'll need to set up your Python environment and install the required libraries.

### Prerequisites
Python 3.x
PyTorch
Torchvision
PIL (Python Imaging Library)
NumPy
Matplotlib

###steps 

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/style-transfer.git
   cd style-transfer


# Install Required Libraries

```bash 
pip install torch torchvision numpy matplotlib pillow


## Usage

To perform style transfer using this model, follow these steps:

# 1. Navigate to the Project Directory
cd path/to/style-transfer

# 2. Run the Notebook
jupyter notebook style_transfer.ipynb


Follow the instructions in the notebook to input your content and style images, and observe the style transfer process.


## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License


This project is open-source and available under the [MIT License](LICENSE).

