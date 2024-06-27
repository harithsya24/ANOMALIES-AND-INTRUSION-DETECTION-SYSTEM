# ANOMALIES-AND-INTRUSION-DETECTION-SYSTEM
This project implements an autoencoder-based anomaly detection system for network data using Python and PyTorch.

## Table of Contents

- [Project Overview](#project-overview)
- [Setup](#setup)
- [Usage](#usage)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Project Overview

The project aims to develop an autoencoder-based anomaly detection system for network data sourced from Kaggle. Anomalies or intrusions are detected by leveraging the compressed representation (latent space) learned by the autoencoder, which captures normal network behavior and identifies deviations.

## Setup

To run this project, ensure you have Python 3.7+ installed. Install the required libraries using pip:

```bash
pip install -r requirements.txt

## Dataset
The project uses the NSL-KDD dataset from Kaggle, which contains network traffic data with both normal and anomalous instances. You can download the dataset from here.

## Training
The autoencoder is trained on normal network traffic to learn a compact representation (latent space). Mean Squared Error (MSE) loss is used for reconstruction error minimization.

**## Evaluation**
The trained model is evaluated on a separate test dataset to assess its ability to detect anomalies in network traffic. Evaluation metrics such as precision, recall, and F1 score are computed.

**## Contributing**
Contributions are welcome! Fork the repository, make improvements, and submit pull requests.

**## Credits**
Dataset:
NSL-KDD Dataset: Sourced from Kaggle user hassan06.
Libraries:
PyTorch: Deep learning framework for building the autoencoder model.
scikit-learn: Machine learning library for data preprocessing and evaluation.
matplotlib: Visualization library for plotting results.

