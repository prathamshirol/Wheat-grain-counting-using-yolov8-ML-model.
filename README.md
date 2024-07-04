
# Wheat Count Detection using YOLOv8

## Overview
This project aims to detect and count wheat in images using the YOLOv8 model. The dataset was custom-made and annotated using Roboflow, and the model was trained and evaluated to perform accurate predictions using Google Colab.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Training and Prediction in Google Colab](#training-and-prediction-in-google-colab)
- [Results](#results)
- [Contributing](#contributing)


## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/wheat-count-detection.git
    cd wheat-count-detection
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset was created and annotated using [Roboflow]([https://roboflow.com/](https://app.roboflow.com/kle-7e0wz/wheat-dataset-new/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true)). The annotations are in YOLO format.
## Training and Prediction in Google Colab
We use Google Colab to train the YOLOv8 model and perform predictions. Follow these steps:

1. Open the [Google Colab notebook](https://colab.research.google.com/drive/114Nf552q9SfT1vqlv6HnyX9cOGp0BhqQ#scrollTo=mQWjYp_66Pyi)

2. Follow the instructions in the notebook to upload the dataset, install necessary libraries, and run the training and prediction code.

3. The notebook will guide you through:
    - Setting up the environment
    - Downloading and preparing the dataset
    - Training the YOLOv8 model
    - Making predictions on test images

## Results
![image](https://github.com/prathamshirol/Wheat-grain-counting-using-yolov8-machine-learning-model./assets/105107078/87b849ff-74e6-4fce-bb04-8f4484aaacf8)
![image](https://github.com/prathamshirol/Wheat-grain-counting-using-yolov8-machine-learning-model./assets/105107078/269e3cce-b877-4afa-b4d9-c393693f186d)


## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue to discuss what you would like to change.


