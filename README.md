## Dogs Breeds Classifier

This project classifies dog breeds using FastAI and PyTorch.  
It's based on transfer learning using a ResNet model and tested on a public dog breeds dataset.

## Structure
Dog_Classifier/
├── notebooks/         # Jupyter notebooks with training, testing, and evaluation
├── src/               # Custom Python scripts (model, training loops, utils)
├── images/            # Visualization results, sample predictions
│   └── dataset_split/ # Contains original training/validation/test images
├── data/              # Any data outputs or references (not versioned directly)
├── dog_breed_model_3.pkl  # Exported model
└── README.md

## Model
- ResNet34
- Trained with FastAI
- Accuracy: 87% on validation set
