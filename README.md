# Multimodal-Sentiment-Analysis-Fusion---Masters-Thesis
Fusion of CNN and RNN models for multimodal sentiment analysis on social media data using MVSA-multiple dataset. Implements text-image fusion with advanced neural architectures for improved sentiment prediction.
# Multimodal Sentiment Analysis Fusion

This repository contains the implementation of a multimodal sentiment analysis model that fuses Recurrent Neural Networks (RNNs) for text and Convolutional Neural Networks (CNNs) for images. The project leverages the MVSA-multiple dataset, which includes paired image-text social media posts annotated with sentiment labels.

## Overview

Social media content is inherently multimodal, often combining text and images to convey sentiment. Traditional sentiment analysis models analyze these modalities separately, which limits their accuracy. This project explores fusion techniques that integrate the strengths of both modalities to improve sentiment prediction.

Key highlights:
- Text sentiment analysis using LSTM (a type of RNN) capturing contextual dependencies in text.
- Image sentiment analysis using DenseNet-121 CNN architecture to extract hierarchical visual features.
- Fusion model combining text and image features with an attention mechanism to dynamically weigh modalities.
- Extensive hyperparameter tuning and evaluation using metrics such as accuracy, precision, recall, and F1 score.
- Experimental results demonstrating modest improvements through fusion, highlighting the challenges of multimodal learning.

## Repository Structure


## Results Summary

| Model              | Validation Accuracy | F1 Score (%) |
|--------------------|---------------------|--------------|
| LSTM (Text only)   | 62.42%              | 48.99        |
| DenseNet-121 (Image only) | 57.50%        | 40.90        |
| Fusion Model        | **74.8**              | **54.80**    |

Statistical tests confirm the fusion model outperforms single modality models, but the margin is small, emphasizing challenges like overfitting and modality redundancy.

## Future Work

- Investigate advanced fusion techniques (e.g., hierarchical or attention-based fusion).
- Address overfitting using alternative architectures or regularization methods.
- Extend to additional modalities such as audio or video.
- Enhance model generalizability across different datasets and social media platforms.
- Optimize models for real-time sentiment analysis applications.
- Improve explainability and interpretability of multimodal models.

## References

- Zhao et al. (2023). [Title]. Journal/Conference.
- Yang et al. (2023). [Title]. Journal/Conference.

## License



---

Feel free to explore, contribute, and improve this repository to push the boundaries of multimodal sentiment analysis!
