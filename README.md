# Pneumonia-using-CNN
<img src="chest_X-ray_for_pneumonia.png" alt="game visual" width="400"/>

## Overview
This study develops a Convolutional Neural Network (CNN) model to automate pneumonia detection using the Kaggle Chest X-Ray Dataset (https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). The model employs two convolutional blocks for feature extraction, followed by dense layers for classification, with data augmentation techniques to address class imbalance. Trained using the Adam optimizer with binary cross-entropy
loss, the model achieved a peak test accuracy of 91%, demonstrating its potential as a reliable diagnostic aid for medical professionals.

## Repository Summary

1. `game_implementation.py`implements the 3-dimensional game, playable by user or computer.

2. Running `playable_game.py` allows the user to play 2048, with specifiable parameters such as the dimensions of the game environment and the desired finishing tile value.

3. Getting to the heart of the project, `model_construction.py` constructs the Dueling Deep Q-Learning model. The neural network is built primarily using `PyTorch`.

4. `training.py` and `testing.py` have the functions to perform training and testing. You can train the model using `execute_training.py`.

5. Finally, `execute_testing.py` lets the AI agent play the game for itself! You can also visualize the gameplay using our implementation with `pygame` and `OpenGL` in the file `visualize_game.py`.
