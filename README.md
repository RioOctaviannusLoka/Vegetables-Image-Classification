<h1 align="center">Image Classification Project</h1>

# Project Overview

This project aims to classify various types of vegetables from images using Convolutional Neural Networks (CNN). The objective is to develop a model that can accurately identify and categorize different vegetables based on their visual features, offering potential applications in fields such as agriculture, food industry, and inventory management.

The model leverages CNNs, a deep learning architecture specifically designed to handle image data, by learning the hierarchical patterns in images. The training process involves using a labeled dataset of vegetable images, and the model's performance is evaluated through accuracy and other relevant metrics.

By the end of this project, the trained CNN model has been saved in multiple formats, including SavedModel, TF-Lite, and TFJS. Inference has been implemented using the SavedModel format providing an overall performance evaluation of the model, demonstrating its performance in real-time vegetable classification tasks.

# Project Structure
```
├───tfjs_model
| ├───group1-shard1of1.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───label.txt
├───saved_model
| ├───saved_model.pb
| └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt
```

# Data Source
The dataset used in this project is taken from [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset?select=Vegetable+Images)