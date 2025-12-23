# Student Performance Prediction - End-to-End Machine Learning Project

This project aims to understand how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental Level of Education, Lunch and Test preparation course.

## Project Structure

```
├── artifacts/          # Generated artifacts (models, preprocessor, headers)
├── catboost_info/      # Catboost model info
├── notebook/           # Jupyter notebooks for EDA and model training
├── src/                # Source code for the project
│   ├── components/     # Data ingestion, transformation, and model training components
│   ├── pipeline/       # Prediction and training pipelines
│   ├── exception.py    # Custom exception handling
│   ├── logger.py       # Logging configuration
│   └── utils.py        # Utility functions (save/load objects)
├── templates/          # HTML templates for the Flask app
├── app.py              # Flask application entry point
├── Dockerfile          # Docker configuration (if applicable)
├── requirements.txt    # Project dependencies
└── setup.py            # Package setup configuration
```

## Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone https://github.com/kpdagrt22/End-to-End-DataScience-Project-with-Azure-AWS-deployment.git
    cd mlproject
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    conda create -p venv python=3.8 -y
    conda activate ./venv
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Flask application**:
    ```bash
    python app.py
    ```

2.  **Access the web interface**:
    Open your browser and navigate to `http://127.0.0.1:5000`.

3.  **Predict**:
    - Click on "Predict your Data" (or navigate to `/predictdata`).
    - Fill in the student details (Gender, Ethnicity, Parental Education, etc.).
    - Submit the form to get the predicted Math Score.

## Technologies Used

-   **Python**: Primary programming language.
-   **Flask**: Web framework for the application.
-   **Pandas, NumPy**: Data manipulation.
-   **Scikit-learn, CatBoost, XGBoost**: Machine learning modeling.
-   **Seaborn, Matplotlib**: Data visualization (in notebooks).
-   **Dill**: Object serialization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

kpdagrt22