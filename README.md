# music-genre-classification

# Genre Classification using MFCC and k-Nearest Neighbors

This project demonstrates a genre classification system using Mel-Frequency Cepstral Coefficients (MFCC) and the k-Nearest Neighbors (k-NN) algorithm. The system aims to classify audio samples into ten different music genres.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview

The goal of this project is to classify music genre based on audio samples using MFCC features and the k-NN algorithm. MFCCs are commonly used in audio processing to represent the timbral features of audio signals. The k-NN algorithm is used to determine the genre of an audio sample based on its similarity to the training dataset.

## Project Structure

- `README.md`: You are here! This document provides an overview of the project.
- `main.py`: The main Python script containing the implementation of the genre classification system.
- `genres_original/`: This directory contains the dataset of audio samples, organized by genre.
- `my.dat`: A serialized file containing the preprocessed dataset used for training and testing.
- `requirements.txt`: A list of Python packages required to run the project.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/genre-classification-mfcc-knn.git
   cd genre-classification-mfcc-knn
   ```

2. Install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Organize your audio samples in the `genres_original/` directory, with subdirectories for each genre.
2. Run the `main.py` script to preprocess the dataset, train the k-NN model, and evaluate its performance:

   ```bash
   python main.py
   ```

3. The script will output the accuracy and best k value for classification, as well as generate a confusion matrix and ROC curves.

4. To classify your own audio sample, modify the `test_file` variable in `main.py` with the path to your audio file and rerun the script.

## Results

The project achieves genre classification by extracting MFCC features from audio samples and using the k-NN algorithm to determine the genre based on similarity. The accuracy and other performance metrics are displayed in the output. Additionally, the confusion matrix and ROC curves provide insight into the model's performance across different genres.


---

Feel free to customize this template based on your specific project details and preferences. Don't forget to replace placeholders like `your-username` with your actual GitHub username and provide accurate paths to your dataset and files.
