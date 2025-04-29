# Genre Classification

This project is a comprehensive implementation of machine learning workflows focused on genre classification. It demonstrates the end-to-end process of building, evaluating, and deploying a machine learning model, showcasing practical skills in data handling, model training, and evaluation.

## Key Features

- Complete ML workflow including data download, preprocessing, data validation, data segregation, model training, and evaluation.
- Utilizes Random Forest classifier for genre classification.
- Integration with MLflow and Weights & Biases (wandb) for experiment tracking and model management.
- Modular project structure for easy maintenance and scalability.
- Automated testing for data quality assurance.

## Technologies and Tools Used

- Python
- scikit-learn (Random Forest)
- pandas, numpy for data manipulation
- MLflow for experiment tracking and model management
- Weights & Biases (wandb) for logging and visualization
- Hydra for configuration management
- pytest for testing

## Project Structure

- `download/`: Scripts and configurations for downloading datasets.
- `preprocess/`: Data preprocessing scripts.
- `check_data/`: Data validation and testing.
- `segregate/`: Data segregation and splitting.
- `random_forest/`: Model training using Random Forest.
- `evaluate/`: Model evaluation and performance analysis.
- `main.py`: Entry point to run the entire ML workflow.
- `config.yaml`: Configuration file for managing project parameters.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Conda or virtual environment setup

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd genre_classification
   ```

2. Create and activate the conda environment:
   ```
   conda env create -f conda.yml
   conda activate genre_classification
   ```

3. Install additional dependencies if needed:
   ```
   pip install -r requirements.txt
   ```

### Running the Project

Run the full ML workflow with:
```
python main.py
```

This will execute all steps from data download to model evaluation.

## Results

The project achieves robust genre classification performance using a Random Forest model. Detailed evaluation metrics and visualizations are logged and can be reviewed through MLflow and wandb dashboards.


