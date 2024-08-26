# Hand Gesture Recognition - Deep Learning Project.

## 🎯 Goal
Recognize hand gestures using state-of-the-art neural networks to control smart TVs without a remote.

## 🔍 Problem Statement

As a data scientist at a home electronics company, your mission is to develop an innovative feature for smart TVs that recognizes five distinct hand gestures, enabling users to control their TV without a remote.

### 🖐️ Gestures and Commands:
- 👍 Thumbs up: Increase volume
- 👎 Thumbs down: Decrease volume
- 👈 Left swipe: Jump backwards 10 seconds
- 👉 Right swipe: Jump forward 10 seconds
- ✋ Stop: Pause the movie

Each gesture is captured as a sequence of 30 frames by a webcam mounted on the TV.

## 📊 Dataset

- Training data: Hundreds of categorized videos
- Video length: 2-3 seconds
- Frame sequence: 30 frames per video
- Recorded by: Various individuals performing gestures
- Data structure: 'train' and 'val' folders with corresponding CSV files
- Video dimensions: 360x360 or 120x160

[Download Dataset](https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL)

## 🚀 Challenge

Train a model on the 'train' folder that performs well on the 'val' folder.

## 🛠️ Technologies Used

- Python
- TensorFlow / PyTorch
- OpenCV
- Numpy
- Pandas

## 🚀 Getting Started

1. Clone this repository
2. Download and extract the dataset
3. Install required dependencies
4. Run the Jupyter notebook or Python scripts
