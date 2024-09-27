# Student Performance Prediction
📚 Predicting Student's Performance Using Machine Learning Models

This project aims to predict student's w\exam performance based on several input factors like gender, race/ethnicity, parental education level, test preparation course, writing score, and reading score. The application utilizes various machine learning algorithms to provide accurate predictions.


# Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-Learn
- CatBoost
- XGBoost
- HTML
- Jupyter Notebook


# Features
* Predict student performance in exams based on input features.
* User-friendly web interface using Flask.
* Real-time predictions based on user input.
* Handles data scaling and preprocessing.
* Supports multiple model comparisons for best performance.

  
# Installation

To set up this project locally, follow these steps -
1. **Clone the repository**:
```bash
https://github.com/saishivaniv/Student-Performance-Prediction.git
```

2.  **Install the required packages**:
   
It's recommended to use a virtual environment. You can create one using `venv` or `conda`.
    
```bash
# For venv
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate
```

```bash
# Install dependencies
pip install -r requirements.txt
```

3. **Run the application**:
```bash
python app.py
```
Access the application at `http://127.0.0.1:5000/`.

## Usage

1. Open your web browser and navigate to `http://127.0.0.1:5000/`.
2. Fill out the form with the required student information.
3. Click the "Predict" button to view the predicted exam scores based on the input data.
4. Review the results displayed on the screen.

## Project Structure

```
student-performance-prediction/
│
├── src/
│   ├── pipeline/
│   │   ├── predict_pipeline.py    # Prediction logic
│   │   └── model_trainer.py       # Model training script
│   ├── logger.py                  # Custom logger implementation
│   └── exception.py               # Custom exception handling
│
├── templates/
│   ├── index.html                 # Homepage
│   ├── home.html                  # Prediction form page
│     
│
├── artifacts/                     # Model and preprocessor artifacts
│
├── app.py                         # Flask application
├── requirements.txt               # Project dependencies
├── README.md                      # This file
└── .gitignore                     # Ignoring unnecessary files

```
