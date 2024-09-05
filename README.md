# Potato Leaf Disease Classification

## Table of Contents
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspects](#technical-aspects)
  * [Dataset](#dataset)
  * [Installation](#installation)
  * [Run](#run)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Contributing](#contributing)
  * [License](#license)
  * [Credits](#credits)

## Demo
Include a gif or image that demonstrates the functionality of your project.

## Overview

This project aims to classify potato leaf images into three categories: Healthy, Early Blight, and Late Blight. Accurate identification of these diseases can help farmers take timely action to prevent crop loss, thereby reducing economic damage.

## Motivation

Potato farmers face significant losses due to diseases like Early Blight and Late Blight. The goal of this project is to provide a tool that helps in early detection of these diseases, allowing for better management and treatment.

## Technical Aspects

This project involves several key steps:
1. Data collection and preprocessing
2. Model training using a convolutional neural network (CNN)
3. Model evaluation
4. Deployment of the model for inference

## Dataset

The dataset used in this project consists of images of potato leaves categorized into three classes: Healthy, Early Blight, and Late Blight. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village).

## Installation

#### Requirements

1. Python 3.6+
2. TensorFlow or PyTorch
3. Docker (optional)
4. AWS account (if deploying on AWS)

#### Steps
1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/potato_leaf_disease.git
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Run

1. Preprocess the data:
    ```sh
    python src/preprocess_data.py
    ```
2. Train the model:
    ```sh
    python src/train_model.py
    ```
3. Evaluate the model:
    ```sh
    python src/evaluate_model.py
    ```
4. (Optional) Deploy the model using Docker or AWS Sagemaker.

## Directory Tree


## To Do

1. Add more data augmentation techniques.
2. Implement different architectures and compare results.
3. Integrate with a real-time monitoring system for deployed models.

## Bug / Feature Request

If you find a bug or have a feature request, please open an issue [here](https://github.com/yourusername/potato_leaf_disease/issues).

## Technologies Used

![TensorFlow](https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg) ![Python](https://www.vectorlogo.zone/logos/python/python-icon.svg) ![Docker](https://www.vectorlogo.zone/logos/docker/docker-icon.svg) ![AWS](https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg)

## Contributing

Contributions are welcome! Please see the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

1. [Kaggle Potato Leaf Dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)
2. [TensorFlow Documentation](https://www.tensorflow.org/)


