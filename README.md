# Handwritten Digit Recognition using Deep Learning

## About the Project
This project uses Deep Learning to recognize handwritten digits from 0 to 9 using the MNIST dataset and TensorFlow/Keras.

## Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- MNIST Dataset

## Model Architecture
1. **Flatten Layer:** Converts the 28×28 image into 784 features.
2. **Dense Layer:** 128 neurons with ReLU activation.
3. **Output Layer:** 10 neurons with Softmax activation for digit classification.

## Model Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Batch Size: 32
- Test Accuracy: Approximately 97.46%

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sundarampd88/Handwritten-Digit-Recognition.git
   ```

2. Open the project folder:
   ```bash
   cd Handwritten-Digit-Recognition
   ```

3. Install the required libraries:
   ```bash
   pip install tensorflow matplotlib numpy streamlit pillow
   ```

4. Run the training notebook `modeltrain.ipynb` to train the model and save it as `digit_model.keras`.

5. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Project Objective
To build a neural network that learns from handwritten digit images and predicts the correct digit.

## Author
Sundaram PD Tiwari
