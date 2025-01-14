# Music Genre Classification using Deep Learning

This project implements a Convolutional Neural Network (CNN)

## Features
- Audio processing using librosa
- Mel spectrogram generation
- CNN-based Classification
- Memory-efficient batch processing
- Data augmentation
- Model evaluation and visualisation 

# Requirements
- Python 3.12.2
- TensorFlow
- Librosa
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The model is designed to work with the GTZAN dataset, which includes 10 genres:
- Blues
- Classical
- Country
- Disco
- Hip-hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

## Usage
1. Install requirements: `pip install -r requirements.txt`
2. Update the data directory path in the notebook
3. Run the notebook cells sequentially

## Model Architecture
The model uses a CNN architecture with:
- Multiple convolutional layers
- Batch normalization
- Max pooling
- Dropout for regularization
- Dense layers for classification

## Results
The model achieves [your accuracy] accuracy on the test set. Detailed evaluation metrics and visualizations are included in the notebook.