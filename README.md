# Grad-CAM Visualization for Parkinson's Disease Detection

This project applies Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize and interpret deep learning model predictions for Parkinson's disease detection using biomedical voice data. The notebook demonstrates how Grad-CAM can highlight which features or regions in the input data most influence the model's decision, supporting explainable AI in medical diagnostics.

## Features

- Loads and preprocesses a Parkinson's disease dataset (e.g., biomedical voice measurements)
- Trains a deep learning model (such as a CNN or MLP) to classify Parkinson's disease vs. healthy controls
- Implements Grad-CAM to visualize class activation maps and interpret model decisions
- Provides visual explanations for model predictions to improve trust and transparency

## Dataset

- **Parkinson's Disease Voice Dataset**  
  Contains biomedical voice measurements from individuals with and without Parkinson's disease  
  [Example dataset on Kaggle](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)[1]  
  - 31 subjects (23 with PD, 8 healthy controls)
  - Features include fundamental frequency, jitter, shimmer, and other voice signal characteristics

## Usage

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1EUbU_E8xHqD2Sjh4B6hMb5cHnjSay4WE).
2. Run all cells to:
   - Download and preprocess the dataset
   - Train a deep learning model for PD detection
   - Apply Grad-CAM to visualize and interpret predictions

## Requirements

- Python 3.x
- TensorFlow / Keras or PyTorch
- NumPy
- Matplotlib
- pandas

Install dependencies with:

```bash
pip install tensorflow numpy matplotlib pandas
```


## Results

- The notebook outputs Grad-CAM visualizations showing which input features most influenced the model's Parkinson’s disease predictions.
- Model performance metrics (accuracy, precision, recall, F1-score) are reported for the classification task.

## License

This project is for educational and research purposes.
