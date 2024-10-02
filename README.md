# Automatic Generation of the Fingers for the Piano

## Introduction
The automatic generation of piano fingerings is an essential topic in the field of music and artificial intelligence. Correct fingering can significantly improve a pianist's ability to play pieces efficiently and comfortably, especially for beginners. Automatic fingering systems aim to assist pianists by generating 
optimal finger sequences for each hand, based on the notes in a musical piece.

In the future, I plan to develop a neural network-based model for the automatic generation of piano fingerings.The goal is to leverage machine learning techniques to predict the best fingering for a given musical piece, reducing the time and effort required to manually decide finger placements.

## Current Progress
As a first step in this project, I have developed a function to convert musical data from a `music21` stream format into PIG dataset format. This conversion is crucial for the subsequent stages of the project, the PIG dataset will be used to train and evaluate models for fingering prediction.

## The PIG Dataset
The **PIG** dataset is a unique and invaluable resource for piano fingering. It contains detailed information about musical pieces, including note sequences and the corresponding fingerings both hands. 


## Future Work
Moving forward, the next steps include:

1. **Preprocessing the data**:  At this stage, I have not yet determined the exact format in which the data will be fed  the neural network. This will be decided in the next stages of development, 
where I will explore various input representations for the network.
2. **Neural Network Development**: Developing and training a neural network to predict fingerings based on musical notes and rhythms.
3. **Evaluation**: Testing and evaluating the model on different piano compositions to ensure that the generated fingerings are practical and efficient.

