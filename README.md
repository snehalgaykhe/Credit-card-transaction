# Credit-card-transaction
This project showcases the use of MLflow for tracking, managing, and visualizing Machine Learning experiments. MLflow enables seamless logging of parameters, metrics, artifacts, and models, making it easier to reproduce experiments and compare different models efficiently.

Preview

<img width="1920" height="1080" alt="Screenshot 2025-09-02 121806" src="https://github.com/user-attachments/assets/99a412c1-2e28-4be8-ab19-35df50b74fe0" />

<img width="1920" height="1080" alt="Screenshot 2025-09-02 121818" src="https://github.com/user-attachments/assets/1786156a-4d7b-4ecd-a9cf-f7a05760554a" />

<img width="1920" height="1080" alt="Screenshot 2025-09-02 121831" src="https://github.com/user-attachments/assets/6fa46a0b-7849-49c1-9b41-14af23c4dfe3" />

<img width="1920" height="1080" alt="Screenshot 2025-09-02 121843" src="https://github.com/user-attachments/assets/95992360-e504-4590-93df-013032d06698" />

<img width="1920" height="1080" alt="Screenshot 2025-09-02 121904" src="https://github.com/user-attachments/assets/e6fb0859-5866-4f73-b181-fd08fce01472" />

🚀 Key Features

📊 Experiment Tracking – Record metrics, parameters, and artifacts.

📂 Model Registry – Store, version, and manage multiple models.

🔄 Reproducibility – Ensure consistent experiment reruns.

📈 Visualization – Compare model performance with an interactive UI.

🔌 Integration – Compatible with scikit-learn, TensorFlow, PyTorch, and custom ML code.

🛠️ Tech Stack

Language: Python

ML Libraries: scikit-learn / TensorFlow / PyTorch

Tracking Tool: MLflow

Data Handling: Pandas, NumPy

📦 Installation

Clone the repository

git clone https://github.com/yourusername/mlflow-experiments.git
cd mlflow-experiments


Install dependencies

pip install -r requirements.txt

▶️ Usage

Start the MLflow UI:

mlflow ui


Open your browser at http://127.0.0.1:5000
 to explore experiment logs.

📂 Project Structure
project/
│── data/          # Dataset
│── notebooks/     # Jupyter notebooks
│── src/           # Source code for training
│── mlruns/        # MLflow experiment logs
│── requirements.txt
│── README.md

📊 Example MLflow Output

After training, MLflow logs include:

Parameters: learning rate, batch size, etc.

Metrics: accuracy, precision, recall, etc.

Artifacts: model files, performance plots, confusion matrices
