Image Caption Generator

This project implements an Image Caption Generator that combines Computer Vision and Natural Language Processing (NLP) to automatically generate descriptive captions for images.

Goals

Extract meaningful features from images using a pretrained Convolutional Neural Network (CNN).

Use caption datasets (e.g., Flickr8k/Flickr30k/MSCOCO) to train the model.

Combine visual features with a sequence model (LSTM/RNN) to generate natural language descriptions.

Evaluate the model by comparing generated captions with ground truth captions.

Demonstrate inference by generating captions for new images.

Workflow

Feature Extraction – Use pretrained CNNs (e.g., VGG16/InceptionV3) to extract image embeddings.

Data Preparation – Load and preprocess caption datasets (tokenization, padding, vocabulary creation).

Model Architecture – Merge image features with text sequences using an LSTM-based model.

Training & Validation – Train on paired image–caption datasets, evaluate with BLEU scores.

Caption Generation – Given a new image, the model predicts the most likely caption.
