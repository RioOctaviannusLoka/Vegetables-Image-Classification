<h1 align="center">Vegetables Image Classification Project</h1>

---

# Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Data Source](#data-source)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

# Project Overview

This project aims to classify various types of vegetables from images using Convolutional Neural Networks (CNN). The objective is to develop a model that can accurately identify and categorize different vegetables based on their visual features, offering potential applications in fields such as agriculture, food industry, and inventory management.

The model leverages CNNs, a deep learning architecture specifically designed to handle image data, by learning the hierarchical patterns in images. The training process involves using a labeled dataset of vegetable images, and the model's performance is evaluated through accuracy and other relevant metrics.

By the end of this project, the trained CNN model has been saved in multiple formats, including SavedModel, TF-Lite, and TFJS. Inference has been implemented using the SavedModel format providing an overall performance evaluation of the model, demonstrating its performance in real-time vegetable classification tasks.

# Project Structure
```
├───saved_model                    # Trained model in saved_model format
| ├───saved_model.pb
| └───variables
├───tfjs_model                     # Trained model in tfjs format
| ├───group1-shard1of4.bin
| ├───group1-shard2of4.bin
| ├───group1-shard3of4.bin
| ├───group1-shard4of4.bin
| └───model.json
├───tflite                         # Trained model in tflite format
| ├───model.tflite
| └───label.txt
├───notebook.ipynb                 # Notebook for data processing and model training
├───README.md                      # Project documentation
└───requirements.txt               # List of dependencies
```

# Data Source

The dataset used in this project is taken from [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset?select=Vegetable+Images)

# Tech Stack

<a href="https://www.python.org/"><img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python Icon" title="Python" width="65" height="65" /></a>
<a href="https://jupyter.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=jupyter" alt="Jupyter Notebook Icon" title="Jupyter Notebook" width="65" height="65" /></a>
<a href="https://pandas.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=pandas" alt="Pandas Icon" title="Pandas" width="65" height="65" /></a>
<a href="https://numpy.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=numpy" alt="Numpy Icon" title="Numpy" width="65" height="65" /></a>
<a href="https://matplotlib.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=matplotlib" alt="Matplotlib" title="Matplotlib" width="65" height="65"/></a>
<a href="http://seaborn.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=seaborn" alt="Seaborn" title="Seaborn" width="65" height="65"/></a>
<a href="https://scikit-learn.org/stable/"><img src="https://go-skill-icons.vercel.app/api/icons?i=scikitlearn" alt="Scikit Learn" title="Scikit Learn" width="65" height="65"/></a>
<a href="https://keras.io/"><img src="https://skills.syvixor.com/api/icons?i=keras" alt="Keras" title="Keras" width="65" height="65"/></a>
<a href="https://www.tensorflow.org/"><img src="https://skills.syvixor.com/api/icons?i=tensorflow" alt="Tensorflow" title="Tensorflow" width="65" height="65"/></a>

# Installation

1. Clone this repository

   ```bash
   git clone https://github.com/RioOctaviannusLoka/Vegetables-Image-Classification.git
   ```

2. Install Python Virtual Environment Library

   ```bash
   pip install virtualenv
   ```

3. Create Python Virtual Environment

   Linux / Mac:

   ```bash
   python3 -m virtualenv venv
   ```

   Windows:

   ```bash
   python -m virtualenv venv
   ```

4. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

5. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

# Usage
1. Activate the Environment

   Linux / Mac:

   ```bash
   source venv\bin\activate
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

2. Open Data Scraping notebook, then run each cell codes

3. Open Sentiment Analysis notebook, then run each cell codes

4. Exit the Virtual Environment

   ```bash
   deactivate
   ```

---

Copyright &copy; 2025 - Rio Octaviannus Loka