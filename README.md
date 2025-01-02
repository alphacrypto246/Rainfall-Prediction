# Rainfall Prediction

## Project Overview
The **Rainfall Prediction** project leverages machine learning techniques to predict rainfall based on various environmental factors. This project incorporates the use of a **Random Forest Classifier** for predictive modeling, **MLflow** for model tracking and experiment management, and a **Flask** web application to serve the model for user interaction.

---

## Features
- **Random Forest Classifier**: Utilized to build an accurate and robust rainfall prediction model.
- **MLflow**: Integrated for tracking experiments, storing model artifacts, and managing the machine learning lifecycle.
- **Flask Application**: Provides an interactive interface for users to input data and receive rainfall predictions.

---

## Tools and Technologies
- **Python**
- **Scikit-learn**
- **MLflow**
- **Flask**
- **Pandas**
- **NumPy**
- **Matplotlib** / **Seaborn** (for visualization, if applicable)

---

## Project Structure
```
Rainfall-Prediction/
|-- data/               # Dataset files
|-- models/             # Saved machine learning models
|-- notebooks/          # Jupyter notebooks for EDA and experimentation
|-- app.py              # Flask application script
|-- requirements.txt    # Python dependencies
|-- mlruns/             # MLflow tracking directory
|-- README.md           # Project documentation (this file)
```

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/alphacrypto246/Rainfall-Prediction.git
   cd Rainfall-Prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up MLflow tracking:
   - Run the MLflow server locally:
     ```bash
     mlflow ui
     ```
   - Access the MLflow UI at `http://localhost:5000`.

5. Run the Flask application:
   ```bash
   python app.py
   ```
   - Access the application at `http://localhost:5000`.

---

## Usage
1. Open the Flask application in your browser.
2. Input the required environmental data (e.g., temperature, humidity, pressure, etc.).
3. Submit the form to receive a prediction on whether rainfall is expected.

---

## Dataset
- The dataset used for training the model includes features such as temperature, humidity, wind speed, and pressure.
- Ensure the dataset is placed in the `data/` directory before running the application.

---

## Model
- The **Random Forest Classifier** was trained using the processed dataset.
- Hyperparameter tuning and evaluation were tracked using **MLflow**.
- Model performance metrics include accuracy, precision, recall, and F1-score.

---

## Future Improvements
- Enhance the user interface for better usability.
- Deploy the application to a cloud platform (e.g., AWS, Heroku, or Azure).
- Experiment with additional machine learning models to improve prediction accuracy.
- Incorporate real-time weather data through APIs.

---

## Author
- **Arya Deep Chowdhury**

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/aryadeepchowdhury/) or reach out via email for any questions or suggestions.

---

## Acknowledgements
- Scikit-learn documentation for clear guidance on model implementation.
- Flask and MLflow communities for providing excellent resources and support.
- [Kaggle](https://www.kaggle.com/) for dataset inspiration and ideas.

