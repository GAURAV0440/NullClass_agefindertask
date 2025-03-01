# NullClass_agefindertask

AgeFinder Project
📌 Overview
This project is an Age Prediction Model that uses a pre-trained machine learning model to estimate a person's age based on input features. It includes a trained model, GUI interface and necessary dependencies to run and test the model.

🚀 Features
1. Pre-trained Machine Learning Model for accurate age prediction.
2. GUI Interface for easy input and predictions.
3. Model Evaluation using accuracy, precision, recall, and confusion matrix.
4. Saved Model & Weights for reuse and testing.
5. Fully Automated Workflow from loading the model to making predictions.

🎯 Model Performance
Evaluated using confusion matrix, precision, recall, and accuracy metrics.
Optimized for performance and accuracy.

📂 Dataset
The dataset used for this project is the UTKFace Dataset, which contains images of faces labeled with age, gender, and ethnicity.
You can access and download the dataset from Kaggle:
👉 UTKFace Dataset
https://www.kaggle.com/datasets/jangedoo/utkface-new

Instructions to Use the Dataset:

Download the dataset from Kaggle.
Extract the files and place them in the dataset/ folder within the project directory.
Ensure the dataset path is correctly referenced in the code.


### 📚 Libraries Used
This project utilizes the following Python libraries:

- **os** - For file and directory operations.
- **NumPy** - For numerical computations and handling arrays.
- **OpenCV (cv2)** - For image processing and face detection.
- **Scikit-Learn** - Used for train-test splitting, confusion matrix, and classification report.
- **TensorFlow / Keras** - Used for deep learning model (MobileNetV2), training, optimization, and evaluation.
- **Matplotlib** - For visualizing training results and model performance.
- **TQDM** - For tracking progress during dataset processing.
- **Tkinter** - For building a GUI interface for user interaction.
- **Pillow (PIL)** - For handling image file formats in the GUI.
