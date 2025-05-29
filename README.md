# Disease-Prediction

This project is a web application that predicts diseases based on user-selected symptoms. Users choose symptoms from a list and receive the most probable disease along with recommended precautions.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Features

- **Symptom Selection:** Users can browse and select multiple symptoms they are experiencing.
- **Disease Prediction:** Uses a trained **Random Forest** machine learning model to predict the most likely disease.
- **Precautionary Advice:** Displays a list of precautions related to the predicted disease.

---

## Technologies Used

- **Frontend:** HTML, CSS  
- **Backend:** Python (Flask)  
- **Machine Learning:** Random Forest algorithm  
- **Data Source:** CSV files (`symptoms_diseases.csv`, `disease_precautions.csv`)  
- **Note:** No database is used. All data is read from CSV files.

---

## Project Structure

DiseasePredictionApp/
│
├── app.py # Flask backend application
├── train_model.py # Model training script
├── rf_model.pkl # Trained Random Forest model
│
├── dataset/
│ ├── symptoms_diseases.csv # Symptoms and their corresponding diseases
│ └── disease_precautions.csv # Precautions for each disease
│
├── static/
│ └── styles.css # Stylesheet
│
├── templates/
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ ├── home.html
│ ├── result.html
│ └── disease_info.html
│
└── README.md

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/RajashekaraRedddy/Disease-Prediction.git
cd Disease-Prediction

### 2. Install Dependencies
```bash
pip install -r requirements.txt

### 3. Run the application
```bash
python app.py

### 4. Open in browser
- Visit http://localhost:5000 in your browser to use the application.

## Usage

- Open the application in your browser.
- Select the symptoms you are experiencing by checking the relevant boxes.
- Click on the **"Submit"** button.
- View the predicted disease along with a list of suggested precautions.

## Contributing

We welcome contributions! Follow these steps to contribute to the project:

1. **Fork** the repository.

2. **Clone** your forked repository:
   ```bash
   git clone https://github.com/your-username/Disease-Prediction.git
   cd Disease-Prediction

3. **Commit** your changes:
   ```bash
git commit -m "Add a new feature"

4. Push to the branch:
   ```bash
git push origin feature-branch

5. Open a **Pull Request** to the main repository.

