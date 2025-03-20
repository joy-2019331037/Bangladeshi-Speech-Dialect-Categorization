# Bangladeshi Speech Dialect Categorization Using Deep Learning

This repository contains the code and resources for classifying Bangladeshi dialects using deep learning techniques. The project explores two approaches: a neural network-based model and a transformer-based Wav2Vec2 model for improved classification accuracy.

## 📌 Project Overview

Bangladesh has a rich variety of dialects that differ across regions. This project aims to develop a system capable of classifying these dialects from speech recordings. We use a dataset of **37,276 audio samples** across **9 dialects**.

## 🏗️ Models Implemented

1. **Neural Network Model**  
   - Extracts MFCC features  
   - Uses a deep learning model with dense layers, batch normalization, and dropout  
   - Achieved **70.64% accuracy** on the test set  

2. **Wav2Vec2 Transformer Model**  
   - Utilizes the pre-trained Wav2Vec2 model for feature extraction  
   - Achieves a better classification accuracy **(around 84%)** than the neural network approach  
   - Works directly on raw waveforms, reducing the need for handcrafted features  

## 📊 Dataset Details

- **Total Samples:** 37,276  
- **Dialects Covered:** Barisal, Chakma, Chittagong, Dhaka, Marma, Noakhali, Rajshahi, Rangpur, Sylhet  
- **Audio Duration:** 5 seconds per sample  


## 🔍 Results & Analysis

| Model |  Accuracy |
|--------|----------|
| Neural Network | 70.64% |
| Wav2Vec2 | 84.13% |

The transformer-based **Wav2Vec2 model outperforms the neural network**, showcasing the effectiveness of self-supervised learning for dialect classification.

## 📌 Future Improvements

- Fine-tuning the Wav2Vec2 model further  
- Exploring other transformer-based models  
- Increasing dataset size for better generalization  

