# Brain Tumor MRI Classification

This repository contains code for classifying brain tumor MRI images into four categories: glioma, meningioma, no tumor, and pituitary tumor. The project leverages deep learning models implemented in PyTorch and includes dataset setup, model training, and evaluation pipelines.

## Features

Dataset Handling: Automatically downloads and organizes the dataset from Kaggle.

Custom Dataset Class: Prepares MRI images with augmentation pipelines for efficient training.

Deep Learning Models: Supports state-of-the-art PyTorch models for image classification.

## Prerequisites

* Python 3.8+

* CUDA-compatible GPU (optional but recommended for training)

## Key Dependencies

* torch, torchvision: For building and training deep learning models.

* albumentations: For image augmentation.

* kagglehub: For downloading the Kaggle dataset.

* cv2, numpy: For image processing.

* scikit-learn: For evaluation metrics.

* matplotlib, seaborn: For data visualization.

## Dataset

The notebook downloads the Brain Tumor MRI dataset from Kaggle and organizes it into training and testing directories. Ensure you have a Kaggle API token set up in your environment before running the script.

## How to Use
1. Clone this repository:
   
   - ```
      git clone https://github.com/youness-marrakchi/tmr-vis-v3.git
      cd tmr-vis-v3
     ```
2. Run the Jupyter Notebook:
   
   - ```
      jupyter notebook tmr_vis_v3.ipynb
     ```
3. Follow the steps in the notebook to:

    - Download and set up the dataset.
  
    - Train the model on MRI images.
  
    - Evaluate and visualize the results.
  
## Future Work

Experiment with additional model architectures and hyperparameters.

Expand the dataset with more diverse examples.

Integrate advanced interpretability techniques.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

[Masoud Nickparvar](https://kaggle.com/masoudnickparvar/brain-tumor-mri-dataset) for the dataset.

Contributors and maintainers of the libraries used in this project.


> [!NOTE]
> This is an ongoing project, and new features and improvements are being actively developed.
