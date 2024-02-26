# LearningWith3DCNN
This repository contains a notebook example for the "Advanced Deep Learning Models and Methods for 3D Spatial Data" course at Politecnico di Milano (Polimi) during the academic year 2023/2024.

## Example Notebook
The notebook in this repository serves as an example showcasing the use of 3D Convolutional Neural Networks (3D CNN) for a specific task related to 3D spatial data. In particular, the example focuses on the application of 3D CNN for human brain skull stripping.

### Dataset
The MRIs used in this example were obtained from [Neurofeedback Skull-stripped (NFBS)](http://preprocessed-connectomes-project.org/NFB_skullstripped/), a dataset of 125 T1-weighted anatomical MRI scans that are manually skull-stripped.

For a comprehensive understanding of the dataset and its preprocessing procedures, please refer to the following publication:
Benjamin Puccio, James P Pooley, John S Pellman, Elise C Taverna, R Cameron Craddock, The preprocessed connectomes project repository of manually corrected skull-stripped T1-weighted anatomical MRI data, GigaScience, Volume 5, Issue 1, December 2016, s13742–016–0150–5, https://doi.org/10.1186/s13742-016-0150-5

### Contents
- `3D_CNN_SkullStripping.ipynb`: Jupyter notebook providing a detailed example of using 3D CNN for skull stripping in human brain images.
- `skull_stripping_net.h5`: Trained 3D CNN model weights for skull stripping.

## Prerequisites
To run the example notebook, ensure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries (e.g., TensorFlow, NumPy, nibabel, nilearn)
