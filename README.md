# Sequential Sentence Classification with CNN

## Overview
This project focuses on the task of sequential sentence classification using Convolutional Neural Networks (CNNs). The goal is to classify biomedical abstract sentences into predefined categories. The CNN model achieves competitive performance, with an accuracy of 76.98%, precision of 77.39%, recall of 76.98%, and F1 score of 77.03%. 

## Approach
1. Data Preprocessing:
   - The dataset was loaded from CSV files and tokenized.
   - Text cleaning techniques were applied to preprocess the sentences.
   - Labels were encoded using one-hot encoding.
2. CNN Model:
   - A CNN architecture was constructed for feature extraction from sequential data.
   - The model consists of convolutional and pooling layers, global max pooling, and dense layers with dropout regularization.
3. Training:
   - The CNN model was trained using the Adam optimizer and categorical cross-entropy loss function.
   - Training history was monitored to detect potential overfitting.
4. Evaluation:
   - The trained CNN model was evaluated on a separate test set using accuracy, precision, recall, and F1 score metrics.

## Discussion
- Model Performance:
  - The CNN model demonstrates competitive performance, effectively capturing local features within sentences. It exhibits faster convergence during training and performs well in understanding patterns within sequential data.
  - However, further exploration and experimentation are needed to maximize its potential in this specific dataset.
  
## Conclusion
- The CNN model offers an effective solution for sequential sentence classification in biomedical abstracts. While it provides computational efficiency and competitive performance, continuous refinement through regularization techniques and hyperparameter tuning is essential to achieve optimal results. 

# Multi-FireArm Audio Detection using Deep Learning

## Features
- Gunshot audio detection using CNNs.
- Achieved an accuracy of 92.56%.
- Utilizes Librosa for audio preprocessing.
- TensorFlow is employed for model development.

## CNN Model Overview
- Utilizes spectrogram features for audio representation.
- Employs convolutional layers to capture spatial hierarchies in the spectrogram.
- Trained using the Adam optimizer and categorical cross-entropy loss.
- Achieves competitive performance in classifying gunshot audio samples.

## LSTM Model Overview
- Processes audio data through Mel-frequency cepstral coefficients (MFCC).
- Utilizes a Bidirectional LSTM architecture to capture temporal dependencies.
- Incorporates mechanisms such as early stopping and learning rate scheduling for training.
- Demonstrates strong performance in classifying gunshot audio samples.

## Discussion
- Both models exhibit high accuracy, precision, recall, and F1-score, indicating their effectiveness in gunshot audio detection.
- The CNN model captures spatial features well, while the LSTM model excels in modeling temporal dependencies.
- Further experimentation and validation on diverse datasets are recommended to enhance model robustness.

## Overview
This project focuses on detecting gunshot audio using Convolutional Neural Networks (CNNs), achieving an accuracy of 92.56%. Leveraging machine learning (ML) and deep learning (DL) techniques, this solution demonstrates proficiency in real-world applications. The project utilizes Librosa for audio preprocessing and TensorFlow for model development.






