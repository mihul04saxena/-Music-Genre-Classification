# Music Genre Classification using KNN (K-Nearest Neighbour) Algorithm

## Project Overview
This project focuses on classifying music genres using the K-Nearest Neighbour (KNN) algorithm. The process includes data collection, preprocessing, feature extraction, model training, evaluation, and visualization.

## Features
1. **Data Collection**: Retrieve music data for various genres, from GTZAN, ![link](https://https//www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
2. **Data Preprocessing**: Clean and prepare data for analysis.
3. **Feature Extraction**: Extract relevant features from the music data.
4. **Model Training**: Train the KNN algorithm to classify music genres.
5. **Model Evaluation**: Assess model performance using various metrics.
6. **Visualization**: Visualize the results and performance of the model.

## Key Components
- **Data Collection**:
  - Use libraries to load music data from local or cloud storage.
  
- **Data Preprocessing**:
  - Handle missing values and normalize data.
  
- **Feature Extraction**:
  - Extract features such as MFCC (Mel-Frequency Cepstral Coefficients), chroma, etc.
  
- **Model Training**:
  - Implement the KNN algorithm to classify music genres.
  
- **Model Evaluation**:
  - Calculate metrics like accuracy, precision, recall, F1-score.
  
- **Visualization**:
  - Plot confusion matrix and classification reports using matplotlib.

## Dataset Information
The dataset used in this project consists of audio files from various music genres. Features extracted from these audio files include:
- **MFCC**: Mel-Frequency Cepstral Coefficients
- **Chroma**: Chroma feature of the audio signal
- **Spectral Contrast**: Spectral contrast of the audio signal

The dataset can be sourced from libraries such as librosa or other public datasets.

## How to Use
1. **Setup**:
   - Install required libraries: `numpy`, `pandas`, `librosa`, `scikit-learn`, `matplotlib`.
   
   ```bash
   pip install numpy pandas librosa scikit-learn matplotlib
