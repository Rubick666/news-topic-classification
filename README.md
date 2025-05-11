# Multiclass News Topic Classification on Reuters Newswires

This project implements a deep learning model for multiclass classification of news articles using the Reuters dataset. The notebook demonstrates all steps from data loading and preprocessing to model building, training, and evaluation using Keras and TensorFlow.

## Features
- Loads and preprocesses the Reuters newswire dataset (46 classes)
- Vectorizes text data for neural network input
- Converts labels to one-hot encoding
- Builds a feedforward neural network with Keras for multiclass classification
- Trains and validates the model, visualizes loss curves

## Technologies Used
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib

## How to Run
1. Open the notebook (`MulticlassClassificationOnReutersNewswires.ipynb`) in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Run all cells in order. The Reuters dataset is automatically downloaded via Keras.
3. (Optional) If running locally, first install the dependencies listed in `requirements.txt`:

    ```
    pip install -r requirements.txt
    ```

## Results
- Achieved over 80% validation accuracy on the Reuters news classification task.
- Training and validation loss/accuracy plots are included in the notebook.

## Dataset
- [Reuters Newswire Topics Classification Dataset](https://keras.io/api/datasets/reuters/)

## Author
- Amirfarhad
