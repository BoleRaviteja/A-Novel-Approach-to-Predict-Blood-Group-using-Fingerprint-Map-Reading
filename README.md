# A Novel Approach to Predict Blood Group Using Fingerprint Map Reading

An experimental B.Tech final-year project exploring fingerprint image analysis and deep learning techniques for blood group prediction.

## 📌 Project Overview

This project investigates the use of fingerprint patterns and image-processing techniques to explore potential relationships between fingerprint characteristics and blood groups.

The application uses a Django web interface to accept fingerprint images and produce predictions using a Convolutional Neural Network (CNN).

**Note:** Fingerprint-based blood group prediction is experimental and is not an established or clinically validated method for determining blood group. Predictions from this project must not be used for medical decisions.

## 🎯 Objectives

- Analyze fingerprint images using image-processing techniques.
- Extract fingerprint features using Gabor filters.
- Explore CNN-based classification.
- Develop a web application for fingerprint image upload and prediction.
- Evaluate the model using appropriate performance metrics.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Web Framework:** Django
- **Deep Learning:** TensorFlow and CNN
- **Image Processing:** OpenCV and Gabor filters
- **Data Processing:** NumPy
- **Frontend:** Update with the actual technologies used in your application

## 📂 Project Structure

```text
fingerprint-blood-group-prediction/
├── Blood/
├── BloodApp/
│   ├── generate_dataset.py
│   ├── train_model.py
│   └── views.py
├── Dataset/
├── model/
├── manage.py
├── requirements.txt
├── run.bat
└── README.md
```

*This is an illustrative structure based on the available project description. Adjust it to match your actual files and folders.*

## ⚙️ Prerequisites

Install the following before running the project:

- Python version compatible with the dependencies in `requirements.txt`
- pip
- Git (optional, for version control)

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/BoleRaviteja/A-Novel-Approach-to-Predict-Blood-Group-using-Fingerprint-Map-Reading.git
```

### 2. Navigate to the project directory

```bash
cd A-Novel-Approach-to-Predict-Blood-Group-using-Fingerprint-Map-Reading
```

### 3. Create a virtual environment

On Windows:

```bash
py -m venv venv
```

### 4. Activate the virtual environment

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Compatibility note:** This project may depend on older versions of Django and TensorFlow. If installation fails, use a Python version compatible with the specified dependencies rather than arbitrarily upgrading packages.

## ▶️ Running the Application

Run these commands from the directory containing `manage.py`.

### 1. Apply database migrations

```bash
python manage.py migrate
```

### 2. Start the Django development server

```bash
python manage.py runserver
```

### 3. Open the application

Visit the following address in your browser:

http://127.0.0.1:8000/

## 🧠 Model and Dataset

### Dataset Generation

The dataset generation script processes fingerprint images using Gabor filters.

```bash
python BloodApp/generate_dataset.py
```

The script is described as generating `X.npy` and `Y.npy` for model training.

### Model Training

The training script trains a CNN model using the generated dataset.

```bash
python BloodApp/train_model.py
```

The documented outputs include model weights and training history. Confirm the actual filenames and output locations in your source code.

### Prediction

The Django application handles fingerprint image uploads and prediction through the application logic in `BloodApp/views.py`.

## 📊 Results and Evaluation

Add your actual experimental results here, including:

- Dataset size and class distribution
- Training and validation accuracy
- Precision, recall, and F1-score, where appropriate
- Confusion matrix
- Sample application screenshots

Do not claim a particular prediction accuracy unless it has been measured and verified.

## ⚠️ Limitations

- Model performance depends on the quality, size, and representativeness of the dataset.
- The relationship between fingerprint patterns and blood groups requires rigorous scientific investigation and independent validation.
- The application is intended for academic experimentation, not clinical diagnosis or blood transfusion decisions.

## 🔮 Future Enhancements

- Improve fingerprint image preprocessing.
- Evaluate alternative machine learning and deep learning architectures.
- Validate results using larger, appropriately collected datasets.
- Improve the application's interface and error handling.
- Add reproducible evaluation and model performance reporting.

## 👨‍🎓 Project Information

**Project Title:** A Novel Approach to Predict Blood Group Using Fingerprint Map Reading

**Project Type:** B.Tech Final-Year Project

## 📄 License

Add an appropriate open-source license if you have the right to distribute the project and its associated materials.

## 🙏 Acknowledgements

This project was developed as part of an undergraduate academic project. Add your institution, project guide, and other acknowledgements as appropriate.
