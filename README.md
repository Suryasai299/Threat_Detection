# ML_TDS
Machine Learning Driven Threat or Malware Detection System

## Overview
A machine learning-based tool that classifies software as benign or malicious based on system usage metrics such as CPU usage, memory usage, and network activity.

## Features
- Classifies files using RandomForest, Gradient Boosting, and XGBoost models.
- Provides a simple web interface for real-time malware classification.
- Uses majority voting from multiple models to determine the final prediction.

## Tech Stack
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Models**: RandomForest, Gradient Boosting, XGBoost
- **Libraries**: scikit-learn, pandas, XGBoost, Flask

# ML-TDS

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Suryasai299/Threat_Detection.git
    cd MCS_ML
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Process the data:**
    ```bash
    python preprocess_data.py
    ```

4. **Train the models:**
    ```bash
    python train_models.py
    ```

5. **Run the Flask app:**
    ```bash
    python app.py
    ```

6. **Access the app:**
   The app link will be generated in the terminal. Look for a line that shows `Running on http://127.0.0.1:5000` (or a similar address). Open that link in your browser.

## How to Use
- Enter system metrics (CPU usage, memory, network activity) in the web form.
- Click "Classify" to get predictions from the trained models.
