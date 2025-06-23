# 🕵️‍♀️ Fraud Detection using Python & Flask

This is a Machine Learning-based fraud detection project developed using **Python** and integrated with an attractive **HTML frontend** via **Flask**. The model analyzes transaction patterns and predicts fraudulent behavior based on historical data.

---

## 🔧 Requirements

Make sure the following tools/libraries are available in your environment:

1. **JupyterLab** or **VS Code** with Python installed
2. Required Python libraries:
   - pandas
   - scikit-learn
   - pickle
   - flask
   - (optional) jupyter
3. **Dataset**:
   - Download the dataset from [Kaggle - PaySim Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)
   - Place it in the project directory

---

## 🚀 How to Run the Project

Follow these steps to train the model and run the web interface:

### 1. Import the Dataset
Place the downloaded CSV file (e.g., `PS_20174392719_1491204439457_log.csv`) inside your project folder.

### 2. Train the Model
- Open and run the notebook `Training Fraud Detection.ipynb`.
- This will:
  - Load and preprocess the data
  - Train a machine learning model
  - Save the model as a `.pkl` file (pickle)

### 3. Launch the Flask App
- Open and run the notebook `app.ipynb`.
- This starts the Flask server with the frontend interface.

### 4. Use the Web Interface
- Navigate to the local URL shown (typically `http://127.0.0.1:5000/`)
- Enter transaction details in the HTML form.
- Submit the form to see the fraud prediction.

---

## 💡 Features

- Real-time fraud prediction based on transaction data
- Clean and simple HTML UI using Flask
- Integrated Machine Learning pipeline
- Easy-to-run Jupyter-based notebooks

---

## 📌 Note

- Ensure all required libraries are installed using `pip install`.
- This project is intended for educational/demo purposes and should not be used for real-world fraud detection without enhancements.

---

Feel free to fork the repo, improve it, or ask for help if needed! 🎯
<!-- Test update for Pull Shark badge -->
