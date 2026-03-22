# CNN Model

## Model Architecture
This model uses a Convolutional Neural Network (CNN) for text classification:
- Embedding layer (converts words into vectors)
- Conv1D layer (extracts local features)
- Global Max Pooling (reduces feature size)
- Dense layer with sigmoid activation (binary classification)

## Techniques Applied
- Tokenization and padding of text sequences
- Word embedding representation
- Convolutional feature extraction
- Binary classification using sigmoid activation
- Adam optimizer and binary cross-entropy loss

## Performance
Accuracy: 0.8909
