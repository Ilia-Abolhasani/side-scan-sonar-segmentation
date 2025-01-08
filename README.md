# Side Scan Sonar Segmentation

This project aims to segment long images of the sea floor using deep learning.

## About

The Side Scan Sonar Segmentation project is developed as a deep learning solution to extract meaningful information from long sea floor images. By utilizing Convolutional Neural Network (CNN) and sliding a fixed-size window across the images, small patches are extracted and used for training the model. The trained model can then segment the images into different classes, achieving the desired segmentation results.

## Usage

1. Open the Jupyter Notebook `side_scan_segmentation.ipynb` in Jupyter Notebook or JupyterLab.

2. Modify the notebook as needed, such as setting the paths to the input images and adjusting the hyperparameters for the CNN model.

3. Execute the notebook cells to perform the following steps:
   - Load the long images of the sea floor.
   - Slide the window across the images to extract small patches for training the model.
   - Train the CNN model using the extracted patches with a batch size of 10.
   - Display the segmentation results and visualize the confusion matrix.

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/Ilia-Abolhasani/side-scan-sonar-segmentation.git
cd side-scan-sonar-segmentation
pip install -r requirements.txt
```
