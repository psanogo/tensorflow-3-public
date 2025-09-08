# TensorFlow Course Public Resources

Welcome to the public resource repository for the TensorFlow course series. This repository contains datasets, pre-trained models, and other materials required to complete the programming assignments and labs.

## 📖 Overview

This storage bucket is a central location for all large files and datasets used throughout the TensorFlow courses. The materials are organized by course, week, and assignment to make them easy to locate.

## 📂 Contents

This repository hosts a variety of datasets and models, including but not limited to:

*   **Image Classification:**
    *   `caltech_birds2010_011.zip`: The Caltech Birds 2010 dataset for bounding box prediction and fine-grained classification.
    *   `cats_vs_dogs.zip`: A classic dataset for binary image classification.
*   **Natural Language Processing:**
    *   `imdb_reviews.json`: A dataset of movie reviews for sentiment analysis.
*   **Time Series:**
    *   `daily-min-temperatures.csv`: A time series dataset for forecasting.

## Usage

The files in this repository can be downloaded directly using tools like `wget` or `curl`. It is recommended to download them into your development environment (e.g., Google Colab, local machine) as instructed in the assignment notebooks.

### Example: Downloading a Dataset

To download a dataset, you can use the following command in your terminal or a notebook cell:

```bash
!wget https://storage.googleapis.com/tensorflow-3-public/datasets/caltech_birds2010_011.zip


