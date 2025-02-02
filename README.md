# SpeechUnderstandingQ2
Speech Understanding Question 2
UrbanSound8K Classification with Random Forest:
This project focuses on classifying audio files from the UrbanSound8K dataset using a Random Forest classifier. The goal is to predict the class of urban sounds based on their acoustic features.

Dataset
The UrbanSound8K dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes:

Air Conditioner
Car Horn
Children Playing
Dog Bark
Drilling
Engine Idling
Gun Shot
Jackhammer
Siren
Street Music

Installation
1. Clone the repository:
	git clone https://github.com/AbhishekSahu87/SpeechUnderstandingQ2.git
	cd SpeechUnderstandingQ2
2. Install the required dependencies:
	pip install -r requirements.txt
3. Download the UrbanSound8K dataset and place it in the data/ directory.

Usage
Preprocessing
Extract acoustic features (e.g., MFCCs, Spectrogram) from the audio files.

Training
Train a Random Forest classifier using the extracted features.

Evaluation
Evaluate the model's performance using metrics such as accuracy, precision and recall.

Generate a confusion matrix to visualize the classification results.

Results
Achieved an accuracy of 90.56% using a Random Forest classifier.

The confusion matrix shows that the model performs well on classes.

Dependencies
Python 3.11.11

Libraries: numpy, pandas, scikit-learn, librosa, matplotlib, seaborn, torch

