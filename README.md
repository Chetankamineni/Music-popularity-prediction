# Music Popularity Prediction

This project focuses on predicting the popularity of Spotify tracks using machine learning techniques. By analyzing a dataset of thousands of songs, the model determines whether a track is likely to be successful based on its intrinsic audio characteristics.

---

## Project Overview

The primary objective is to build a predictive framework to estimate song popularity scores (0–100) using Python and data science principles. The project involves data preprocessing, exploratory analysis, and model evaluation to identify the features that define a popular track.

---

## Dataset

**Source:**  [Spotify Tracks Dataset](https://www.kaggle.com/)  
The dataset contains key audio features for thousands of tracks, including:

* **Danceability**: Suitability of a track for dancing.
* **Acousticness**: Confidence measure of whether the track is acoustic.
* **Energy**: Perceptual measure of intensity and activity.
* **Speechiness**: Presence of spoken words in a track.
* **Tempo**: Overall estimated beats per minute (BPM).
* **Duration**: The length of the track.

**Target variable:** `popularity` score (0–100).

---

## Technical Stack

* **Language**: Python
* **Data Manipulation**: Pandas and NumPy
* **Machine Learning**: Scikit-learn
* **Visualization**: Matplotlib and Seaborn
* **Environment**: Jupyter Notebook / Google Colab

---

## Methodology

1. **Data Preprocessing**: Cleaning the dataset, handling null values, managing data types, and scaling features.
2. **Exploratory Data Analysis (EDA)**: Conducting in-depth analysis to understand the correlation between audio features and song success.
3. **Model Training**: Implementing several machine learning models, including:
   * Logistic Regression
   * Random Forest
   * Gradient Boosting
4. **Evaluation**: Assessing performance using metrics such as accuracy, precision, and recall.
5. **Inference**: Applying the trained model to make predictions on unseen data.

---

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Chetankamineni/music-popularity
   cd music-popularity
   ```
3. **Install dependencies**: You need to have the following Python libraries installed:
   
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```
5. **Execute the notebook**: Open `spotify_pop_predictor.ipynb` in a Jupyter environment to view the full analysis and run the training pipeline.
