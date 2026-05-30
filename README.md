# 🎭 Mask Detector

A machine learning project that detects face masks in real-time video streams using a trained neural network model.

## 📌 Overview

This project implements an automated mask detection system that analyzes video feeds and classifies individuals as **wearing** or **not wearing** a face mask. Built with Python and Jupyter Notebook, it demonstrates practical applications of computer vision and machine learning.

## ✨ Features

- **Real-time Detection**: Process live video streams
- **ML-Powered**: Uses a trained deep learning model for accurate mask classification
- **Easy to Use**: Interactive Jupyter Notebook implementation
- **Dataset Ready**: Includes data_sets folder for model training

## 📂 Project Structure

```
mask-detector/
├── mask_detector.ipynb    # Main notebook with model and implementation
└── data_sets/             # Training and validation datasets
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- OpenCV
- TensorFlow/PyTorch (or relevant ML framework)

### Installation

1. Clone this repository
   ```bash
   git clone https://github.com/jasocami/mask-detector.git
   cd mask-detector
   ```

2. Install dependencies
   ```bash
   pip install jupyter opencv-python tensorflow
   ```

3. Open and run the notebook
   ```bash
   jupyter notebook mask_detector.ipynb
   ```

## 📊 Dataset

The `data_sets` folder contains images for training and testing the model. Ensure proper data organization before running the notebook.

## 🔧 How It Works

1. **Input**: Webcam or video file
2. **Processing**: ML model analyzes faces
3. **Output**: Real-time mask detection predictions

## 📖 Usage

Open `mask_detector.ipynb` in Jupyter and follow the cells to:
- Load and preprocess data
- Train the model
- Evaluate performance
- Run real-time detection

## 🤝 Contributing

Contributions welcome! Feel free to:
- Submit issues for bugs or feature requests
- Fork and create pull requests
- Improve documentation or model accuracy

## 📄 License

This project is open source and available for educational and commercial use.