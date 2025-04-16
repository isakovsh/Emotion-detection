![A](https://github.com/isakovsh/Emotion-detection/blob/master/image.png?raw=True)
# 🎧 Audio Emotion Recognition using Deep Learning

This project aims to recognize emotions from audio signals using deep learning techniques. It processes `.wav` audio files, extracts meaningful features like MFCCs (Mel Frequency Cepstral Coefficients), and uses a neural network to classify the emotional tone in speech.

The notebook walks through data loading, preprocessing, model training, evaluation, and performance visualization.

---

## 📁 Project Structure
```

├── isakovshohrukh-audioemotion.ipynb # Main Jupyter Notebook for training and evaluating the model
├── final_model.h5       # Trained TensorFlow model
├── final_data.csv       # Final dataset with extracted features
├── requirements.txt     # Project dependencies
├── README.md            # Project overview and instructions
```
## 🚀 Features

- Audio preprocessing with `librosa`  
- MFCC feature extraction  
- Label encoding for emotion classes  
- Neural network (MLP) for classification  
- Accuracy tracking and confusion matrix visualization  

Supported emotion labels include:

```
['neutral', 'calm', 'happy', 'sad', 'angry', 'fearful', 'disgust', 'surprised']
```

---

## 🧰 Requirements

Install required libraries via pip:

```bash
pip install numpy pandas librosa matplotlib scikit-learn tensorflow
```

Or use a `requirements.txt` file:

```text
numpy
pandas
librosa
matplotlib
scikit-learn
tensorflow
```

---

## 📊 Dataset

- Each `.wav` file contains a speech clip expressed with a specific emotion.
- The dataset should follow a naming convention or directory structure from which emotion labels can be parsed. 

## Results 
![A](https://github.com/isakovsh/Emotion-detection/blob/master/results.png?raw=True)
---





