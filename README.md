# Sound Event Recognition

## Project Description

This project aims to develop methods for detecting and recognizing sound events based on spectral features of audio signals obtained via Short-Time Fourier Transform (STFT). Applications include machine monitoring, urban environment analysis, noise pollution tracking, and audio clip classification.

## Features

* Extraction of spectral features such as peak energy, spectral centroid, spectral flux, MFCC, and others using Python and the Librosa library.
* Implementation of a classifier based on the k-Nearest Neighbors (k-NN) algorithm for sound event classification.
* Visualization of spectrograms and detected sound events.
* Performance evaluation using accuracy metrics and confusion matrices on test datasets.

## Dataset

The project uses selected classes from the UrbanSounds8k dataset, specifically: dog\_bark, gun\_shot, and street\_music. Training and testing samples are organized in separate folders according to their classes. A longer mixed audio file (`mix.wav`) is used for event detection tasks.

## How to Run

1. Install required Python packages (e.g., librosa, numpy, scikit-learn, matplotlib).
2. Extract spectral features from audio samples.
3. Train the k-NN classifier on training data.
4. Evaluate the classifier on test data and analyze results.

## Deliverables

* Jupyter Notebook with all implemented code and explanations.
* Visualizations of spectrograms, features, and detection results.
* Tables and graphs summarizing classification performance.
* Analysis of strengths, weaknesses, and suggestions for improvement.
* Instructions for usage.

