# Predictive Maintenance AI for Manufacturing Plants

## Project Description
This project aims to develop a predictive maintenance AI system for manufacturing plants to reduce downtime and optimize maintenance schedules. The system uses sensor data to predict equipment failures before they occur.

## Directory Structure
- `data/`: Contains the datasets used in the project.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model training.
- `src/`: Source code for data preprocessing, feature engineering, model training, and the dashboard.
- `Dockerfile`: Instructions to build a Docker image for the project.
- `requirements.txt`: List of dependencies for the project.
- `README.md`: Project documentation.
- `app.py`: Main entry point for the application.

## Setup
1. Clone the repository.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the data preprocessing script:
    ```bash
    python src/data_preprocessing.py
    ```
4. Run the feature engineering script:
    ```bash
    python src/feature_engineering.py
    ```
5. Train the model:
    ```bash
    python src/model_training.py
    ```
6. Run the dashboard:
    ```bash
    streamlit run src/dashboard.py
    ```

## Deployment
To deploy the project using Docker:
1. Build the Docker image:
    ```bash
    docker build -t predictive_maintenance .
    ```
2. Run the Docker container:
    ```bash
    docker run -p 8501:8501 predictive_maintenance
    ```

## Authors
- Prince Donda
- Priyanshu Galani
- Dhruv Kathrotiya
- Tirth Godhani
