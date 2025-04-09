# MLOps Experiment Tracking Using MLflow

This repository demonstrates how to perform experiment tracking using [MLflow](https://mlflow.org/), an open-source platform for managing the end-to-end machine learning lifecycle.

## Features

- **Experiment Tracking**: Log and compare multiple machine learning experiments using MLflow's tracking API.
- **Automatic Logging**: Utilize MLflow's autologging feature to capture parameters, metrics, and artifacts without manual intervention.
- **Visualization**: Generate and save confusion matrices to evaluate model performance.

## Repository Structure

- `mlruns/`: Directory containing MLflow experiment logs.
- `src/`: Source code for model training and evaluation.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `Confusion-matrix.png`: Sample confusion matrix image.
- `LICENSE`: MIT License for the project.
- `README.md`: This README file.
- `mlflow-autolog.txt`: Documentation or notes related to MLflow autologging.
- `mlflow-basics.txt`: Documentation or notes on basic MLflow usage.
- `requirements.txt`: List of Python dependencies required for the project.
- `template.py`: Template script for setting up MLflow tracking in a project.

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Anand21J-V/MLOPs-Experiment-Tracking-Using-MLFLOW.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd MLOPs-Experiment-Tracking-Using-MLFLOW
   ```

3. **Create a virtual environment** (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
   ```

4. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run the template script** to start tracking experiments:

   ```bash
   python template.py
   ```

   This script will execute a machine learning experiment and log the parameters, metrics, and artifacts using MLflow.

6. **View the MLflow UI**:

   After running the script, start the MLflow UI to visualize the logged experiments:

   ```bash
   mlflow ui
   ```

   Open a web browser and navigate to `http://localhost:5000` to explore the experiment runs.

## Dependencies

The project relies on the following Python packages:

- `mlflow`
- `scikit-learn`
- `matplotlib`

Ensure these packages are installed by using the `requirements.txt` file provided.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Anand Vishwakarma

---

For more information on MLflow and its capabilities, visit the [official MLflow documentation](https://mlflow.org/docs/latest/index.html). 
