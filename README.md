# Air Quality Index (AQI) Predictor 🌍

This project predicts the **Air Quality Index (AQI)** using machine learning techniques.  
The model is first trained on a dataset and saved as a `.joblib` file.  
After training, the saved model is used in the application (`app.py`) to make predictions.

---

## 📌 Project Workflow

1. **Train the Machine Learning Model**
2. **Save the trained model as `.joblib`**
3. **Run the application to predict AQI**

---

## 📂 Project Structure

Air-Quality-Index-Predictor/
│
├── dataset/
│ └── air_quality_data.csv        #link for dataset https://drive.google.com/file/d/1yE618Pk9J6CXMZCVa1VEr3p2B8j1UjcU/view?usp=drive_link
│
├── Train.py
├── app.py
├── requirements.txt
└── model.joblib

Install required libraries:

----bash
    python -m pip install -r requirements.txt

Step 1: Train the Model

    The training script uses the dataset to:

    Load and preprocess air quality data

    Train a machine learning model

    Save the trained model in .joblib format

    Run the training file:

    python Train.py


    After successful training, a model file will be created:

    model.joblib


    ⚠️ Important:
      Do not run app.py before training.
      The application depends on the .joblib model file.

▶️ Step 2: Run the Application

    Once the model is trained and saved, run the application:

    python app.py


    The application loads the trained .joblib model and predicts the Air Quality Index (AQI) based on input values.

    📊 Features Used for Prediction

      PM2.5

      PM10

      NO2

      SO2

      CO

      O3
  (Features may vary depending on dataset)

  🧪 Technologies Used
      Python
      NumPy
      Pandas
      Scikit-learn
      Joblib

Matplotlib / Seaborn (for visualization)

✅ Output

    Trained model saved as .joblib

    AQI prediction based on environmental parameters

🚀 Future Enhancements
    Real-time AQI data integration
    Web-based UI
    Deep Learning models
    API deployment
