# Composer Identification and Music Genre Classification

<a href="https://www.kaggle.com/datasets/blanderbuss/midi-classic-music">Kaggle MIDI Classic Music Dataset</a>

## Project Overview
This project aims to develop a deep learning model that accurately predicts the composer of a given musical score. By leveraging Long Short-Term Memory (LSTM) networks and Convolutional Neural Networks (CNN), the model is trained to identify compositions by Bach, Beethoven, Chopin, and Mozart. The project involves data collection, preprocessing, feature extraction, model building, training, evaluation, and optimization.

## Table of Contents
* Introduction
* Dataset
* Methodology
* Feature Extraction
* Model Architecture
* Training and Evaluation
* Results
* Conclusion and Future Work
* License

## Introduction
Music, a form of art with a rich history, features distinct styles from various composers. This project addresses the challenge of identifying the composer of a musical piece using deep learning techniques. The goal is to develop a robust model that can accurately classify compositions by four renowned composers.

## Dataset
The dataset used for this project is sourced from Kaggle and contains MIDI files of classical compositions by Bach, Beethoven, Chopin, and Mozart. The dataset includes 3,929 MIDI files labeled with the composer's name.

## Methodology
The project workflow includes:

* Data Collection: Gathering MIDI files from the dataset.
* Data Preprocessing: Cleaning and organizing the data.
* Feature Extraction: Extracting key features such as length, number of notes, note frequencies, tempo changes, polyphony, time signatures, and key signatures.
* Model Building: Constructing LSTM and CNN models to classify the musical scores.
* Training: Training the models on the preprocessed data.
* Evaluation: Assessing model performance using accuracy, precision, and recall metrics.
* Optimization: Fine-tuning hyperparameters to improve model accuracy.

## Libraries and Frameworks Used
* Mido: Used for reading and writing MIDI files, and handling MIDI messages.
* Pandas: Data manipulation and analysis.
* Numpy: Numerical operations.
* Scikit-learn: Preprocessing data, encoding labels, splitting datasets, evaluating model performance.
* TensorFlow/Keras: Building, training, and evaluating deep learning models.
* Matplotlib and Seaborn: Data visualization.

## Feature Extraction
Key features extracted from the MIDI files include:

* Length: Duration of each MIDI file.
* Number of Notes: Total number of notes.
* Note Frequencies: Frequency distribution of notes.
* Tempo Changes: Variations in tempo.
* Polyphony: Number of simultaneous notes played.
* Time Signatures: Rhythmic structures.
* Key Signatures: Tonal frameworks.

## Model Architecture
The project uses two primary models:

* LSTM Network: Captures long-term dependencies and temporal structures in the music.
* CNN: Analyzes the sequential data of music for pattern recognition.

## Training and Evaluation
The models are trained using the extracted features, with performance evaluated through metrics such as accuracy, precision, and recall. Data augmentation techniques like pitch shifting are used to handle class imbalance.

## Results
The models achieved high accuracy in predicting the composers of the musical scores. Visualizations such as confusion matrices and training history plots illustrate model performance.

## Conclusion and Future Work
The project demonstrates the potential of deep learning in music analysis, contributing to the integration of technology and the arts. The models developed can assist in identifying composers of classical music pieces, making them useful for musicians, educators, and researchers. Future work could explore expanding the dataset to include more composers, improving the model architecture, and integrating these models into music recommendation systems and educational tools.

## License
This project is licensed under the MIT License. See the <a href="https://github.com/zainnobody/AAI-511-Final-Project/tree/main?tab=MIT-1-ov-file">LICENSE</a> file for details.
