# TF Model to OpenVINO IR and Inference
Multi-Class Image Classification for Computer Aided Gastrointestinal Disease Detection

## Data source and Description 
The data can be found here https://www.kaggle.com/datasets/meetnagadia/kvasir-dataset.

## Model Training
The VGG-19 pre-trained model was used in prodcing the CNN model and the code can is available as: `endoscopy.ipynb`.

## Objective
The objective of this project is to take the model and transform it to OpenVINO IR format then deploy it for inference.

The script for implementing the OpenVINO IR coversion and inference is available as: `endoscopy_inference.ipynb`.
